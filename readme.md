# WP Job Manager #
**Contributors:** [mikejolley](https://profiles.wordpress.org/mikejolley), [automattic](https://profiles.wordpress.org/automattic), [adamkheckler](https://profiles.wordpress.org/adamkheckler), [annezazu](https://profiles.wordpress.org/annezazu), [cena](https://profiles.wordpress.org/cena), [chaselivingston](https://profiles.wordpress.org/chaselivingston), [csonnek](https://profiles.wordpress.org/csonnek), [davor.altman](https://profiles.wordpress.org/davor.altman), [drawmyface](https://profiles.wordpress.org/drawmyface), [erania-pinnera](https://profiles.wordpress.org/erania-pinnera), [jacobshere](https://profiles.wordpress.org/jacobshere), [jakeom](https://profiles.wordpress.org/jakeom), [jeherve](https://profiles.wordpress.org/jeherve), [jenhooks](https://profiles.wordpress.org/jenhooks), [jgs](https://profiles.wordpress.org/jgs), [jonryan](https://profiles.wordpress.org/jonryan), [kraftbj](https://profiles.wordpress.org/kraftbj), [lamdayap](https://profiles.wordpress.org/lamdayap), [lschuyler](https://profiles.wordpress.org/lschuyler), [macmanx](https://profiles.wordpress.org/macmanx), [nancythanki](https://profiles.wordpress.org/nancythanki), [orangesareorange](https://profiles.wordpress.org/orangesareorange), [rachelsquirrel](https://profiles.wordpress.org/rachelsquirrel), [ryancowles](https://profiles.wordpress.org/ryancowles), [richardmtl](https://profiles.wordpress.org/richardmtl), [scarstocea](https://profiles.wordpress.org/scarstocea)  
**Tags:** job manager, job listing, job board, job management, job lists, job list, job, jobs, company, hiring, employment, employer, employees, candidate, freelance, internship, job listings, positions, board, application, hiring, listing, manager, recruiting, recruitment, talent  
**Requires at least:** 4.1  
**Tested up to:** 4.8  
**Stable tag:** 1.26.2  
**License:** GPLv3  
**License URI:** http://www.gnu.org/licenses/gpl-3.0.html  

Manage job listings from the WordPress admin panel, and allow users to post job listings directly to your site.

## Description ##

WP Job Manager is a **lightweight** job listing plugin for adding job-board like functionality to your WordPress site. Being shortcode based, it can work with any theme (given a bit of CSS styling) and is really simple to setup.

### Features ###

* Add, manage, and categorize job listings using the familiar WordPress UI.
* Searchable & filterable ajax powered job listings added to your pages via shortcodes.
* Frontend forms for guests and registered users to submit & manage job listings.
* Allow job listers to preview their listing before it goes live. The preview matches the appearance of a live job listing.
* Each listing can be tied to an email or website address so that job seekers can apply to the jobs.
* Searches also display RSS links to allow job seekers to be alerted to new jobs matching their search.
* Allow logged in employers to view, edit, mark filled, or delete their active job listings.
* Developer friendly code — Custom Post Types, endpoints & template files.

The plugin comes with several shortcodes to output jobs in various formats, and since its built with Custom Post Types you are free to extend it further through themes.

[Read more about WP Job Manager](https://wpjobmanager.com/).

### Documentation ###

Documentation for the core plugin and add-ons can be found [on the docs site here](https://wpjobmanager.com/documentation/). Please take a look before requesting support because it covers all frequently asked questions!

### Add-ons ###

The core WP Job Manager plugin is free and always will be. It covers all functionality we consider 'core' to running a simple job board site.

Additional, advanced functionality is available through add-ons. Not only do these extend the usefulness of the core plugin, they also help fund the development and support of core.

You can browse available add-ons after installing the plugin by going to `Job Listings > Add-ons`. Our popular add-ons include:

**[Applications](https://wpjobmanager.com/add-ons/applications/)**

Allow candidates to apply to jobs using a form & employers to view and manage the applications from their job dashboard.

**[WooCommerce Paid Listings](https://wpjobmanager.com/add-ons/wc-paid-listings/)**

Paid listing functionality powered by WooCommerce. Create custom job packages which can be purchased or redeemed during job submission. Requires the WooCommerce plugin.

**[Resume Manager](https://wpjobmanager.com/add-ons/resume-manager/)**

Resume Manager is a plugin built on top of WP Job Manager which adds a resume submission form to your site and resume listings, all manageable from WordPress admin.

**[Job Alerts](https://wpjobmanager.com/add-ons/job-alerts/)**

Allow registered users to save their job searches and create alerts which send new jobs via email daily, weekly or fortnightly.

**[Core add-on bundle](https://wpjobmanager.com/add-ons/bundle/)**

You can get the above add-ons and several others at discount with our [Core Add-on Bundle](https://wpjobmanager.com/add-ons/bundle/). Take a look!

### Contributing and reporting bugs ###

You can contribute code to this plugin via GitHub: [https://github.com/Automattic/WP-Job-Manager](https://github.com/Automattic/WP-Job-Manager) and localizations via [https://translate.wordpress.org/projects/wp-plugins/wp-job-manager](https://translate.wordpress.org/projects/wp-plugins/wp-job-manager)

Thanks to all of our contributors.

### Support ###

Use the WordPress.org forums for community support where we try to help all users. If you spot a bug, you can log it (or fix it) on [Github](https://github.com/Automattic/WP-Job-Manager) where we can act upon them more efficiently.

If you need help with one of our add-ons, [please raise a ticket in our help desk](https://wpjobmanager.com/support/).

If you want help with a customisation, please consider hiring a developer! [http://jobs.wordpress.net/](http://jobs.wordpress.net/) is a good place to start.

## Installation ##

### Automatic installation ###

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't even need to leave your web browser. To do an automatic install, log in to your WordPress admin panel, navigate to the Plugins menu and click Add New.

In the search field type "WP Job Manager" and click Search Plugins. Once you've found the plugin you can view details about it such as the point release, rating and description. Most importantly of course, you can install it by clicking _Install Now_.

### Manual installation ###

The manual installation method involves downloading the plugin and uploading it to your web server via your favorite FTP application.

* Download the plugin file to your computer and unzip it
* Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installation's `wp-content/plugins/` directory.
* Activate the plugin from the Plugins menu within the WordPress admin.

### Getting started ###

Once installed:

1. Create a page called "jobs" and inside place the `[jobs]` shortcode. This will list your jobs.
2. Create a page called "submit job" and inside place the `[submit_job_form]` shortcode if you want front-end submissions.
3. Create a page called "job dashboard" and inside place the `[job_dashboard]` shortcode for logged in users to manage their listings.

**Note when using shortcodes**, if the content looks blown up/spaced out/poorly styled, edit your page and above the visual editor click on the 'text' tab. Then remove any 'pre' or 'code' tags wrapping your shortcode.

For more information, [read the documentation](https://wpjobmanager.com/documentation/).

## Frequently Asked Questions ##

### How do I setup WP Job Manager? ###
View the getting [installation](https://wpjobmanager.com/document/installation/) and [setup](https://wpjobmanager.com/document/setting-up-wp-job-manager/) guide for advice getting started with the plugin. In most cases it's just a case of adding some shortcodes to your pages!

### Can I use WP Job Manager without frontend job submission? ###
Yes! If you don't setup the [submit_job_form] shortcode, you can just post from the admin backend.

### How can I customize the job application process? ###
There are several ways to customise the job application process in WP Job Manager, including using some extra plugins (some are free on Wordpress.org).

See: [Customising the Job Application Process](https://wpjobmanager.com/document/customising-job-application-process/)

### How can I customize the job submission form? ###
There are three ways to customise the fields in WP Job Manager;

1. For simple text changes, using a localisation file or a plugin such as https://wordpress.org/plugins/say-what/
2. For field changes, or adding new fields, using functions/filters inside your theme's functions.php file: [https://wpjobmanager.com/document/editing-job-submission-fields/](https://wpjobmanager.com/document/editing-job-submission-fields/)
3. Use a 3rd party plugin such as [https://plugins.smyl.es/wp-job-manager-field-editor/](https://plugins.smyl.es/wp-job-manager-field-editor/?in=1) which has a UI for field editing.

If you'd like to learn about WordPress filters, here is a great place to start: [https://pippinsplugins.com/a-quick-introduction-to-using-filters/](https://pippinsplugins.com/a-quick-introduction-to-using-filters/)

### How can I be notified of new jobs via email? ###
If you wish to be notified of new postings on your site you can use a plugin such as [Post Status Notifier](http://wordpress.org/plugins/post-status-notifier-lite/).

### What language files are available? ###
You can view (and contribute) translations via the [translate.wordpress.org](https://translate.wordpress.org/projects/wp-plugins/wp-job-manager).

## Screenshots ##

1. The submit job form.
2. Submit job preview.
3. A single job listing.
4. Job dashboard.
5. Job listings and filters.
6. Job listings in admin.

## Changelog ##

### 1.26.2 ###
* Fix: Prevents use of Ajax file upload endpoint for visitors who aren't logged in. Themes should check with `job_manager_user_can_upload_file_via_ajax()` if using endpoint in templates.  (https://github.com/Automattic/WP-Job-Manager/pull/1020)
* Fix: Escape post title in WP Admin's Job Listings page and template segments. (Props to @EhsanCod3r; https://github.com/Automattic/WP-Job-Manager/pull/1026)

### 1.26.1 ###
* Enhancement: Add language using WordPress's current locale to geocode requests. (@jom; https://github.com/Automattic/WP-Job-Manager/pull/1007)
* Fix: Allow attempts to use Google Maps Geocode API without an API key. (@spencerfinnell; https://github.com/Automattic/WP-Job-Manager/pull/998)
* Fix: Issue affecting job expiry date when editing a job listing. (@spencerfinnell, @jom; https://github.com/Automattic/WP-Job-Manager/pull/1008)
* Fix: Show correct total count of results on `[jobs]` shortcode. (@jom; https://github.com/Automattic/WP-Job-Manager/pull/1006)

### 1.26.0 ###
* Enhancement: Warn the user if they're editing an existing job. (@donnchawp; https://github.com/Automattic/WP-Job-Manager/pull/847)
* Enhancement: WP Admin Job Listing page's table is now responsive. (@turtlepod; https://github.com/Automattic/WP-Job-Manager/pull/906)
* Enhancement: New setting for hiding expired listings from `[jobs]` filter. (@turtlepod; https://github.com/Automattic/WP-Job-Manager/pull/903)
* Enhancement: Use WP Query's built in search function to improve searching in `[jobs]`. (@jom; https://github.com/Automattic/WP-Job-Manager/pull/960)
* Fix: Job Listing filter only searches meta fields with relevant content. Add custom fields with `job_listing_searchable_meta_keys` filter. (@turtlepod; https://github.com/Automattic/WP-Job-Manager/pull/910)
* Fix: Improved support for WPML and Polylang. (@jom; https://github.com/Automattic/WP-Job-Manager/pull/963)
* Fix: Expired field no longer forces admins to choose a date in the future. (@turtlepod; https://github.com/Automattic/WP-Job-Manager/pull/903)
* Fix: Listings with expiration date in past will immediately expire; moving to Active status will extend if necessary. (@turtlepod, @jom; https://github.com/Automattic/WP-Job-Manager/pull/903, https://github.com/Automattic/WP-Job-Manager/pull/975)
* Fix: Google Maps API key setting added to fix geolocation retrieval on new sites. (@jom; https://github.com/Automattic/WP-Job-Manager/pull/912)
* Fix: Issue when duplicating a job listing with a field for multiple file uploads. (@turtlepod; https://github.com/Automattic/WP-Job-Manager/pull/911)
* Fix: Hide page results when adding links in the `[submit_job_form]` shortcode. (@jom; https://github.com/Automattic/WP-Job-Manager/pull/922)
* Fix: Job feed now loads when a site has no posts. (@dbtlr; https://github.com/Automattic/WP-Job-Manager/pull/870)
* Fix: No error is thrown when deleting a user. (@tripflex; https://github.com/Automattic/WP-Job-Manager/pull/875)
* Dev: Plugins and themes can now retrieve JSON of Job Listings results without HTML. (@spencerfinnell; https://github.com/Automattic/WP-Job-Manager/pull/888)
* Dev: Updated inline documentation.

### 1.25.3 ###
* Enhancement: Allow job types to be optional, just like categories. https://github.com/automattic/wp-job-manager/pull/789 Props Donncha.
* Enhancement: Add get_job_listing_types filter. https://github.com/automattic/wp-job-manager/pull/824 Props Adam Heckler.
* Enhancement: Various date format setting improvements. See https://github.com/automattic/wp-job-manager/pull/757 Props Christian Nolen.
* Enhancement: Pass search values with the job_manager_get_listings_custom_filter_text filter. https://github.com/automattic/wp-job-manager/pull/845 Props Kraft.
* Fix: Prevent a potential CSRF vector. https://github.com/automattic/wp-job-manager/pull/891 Props Jay Patel for the responsible disclosure.
* Fix: Improve load time by removing unnecessary oEmbed call. https://github.com/automattic/wp-job-manager/pull/768 Props Myles McNamara.
* Fix: Improve WPML compatability. https://github.com/automattic/wp-job-manager/pull/787 Props Spencer Finnell.
* Fix: Add an implicit whitelist for API requests. https://github.com/automattic/wp-job-manager/pull/855 Props muddletoes.
* Fix: Fixed taxonomy search conditions. See https://github.com/automattic/wp-job-manager/pull/859/ Props Jonas Vogel.

### 1.25.2 ###
* Fix - The date format of the expiry date picker was incorrect in translations so we added a comment to clarify, and fixed translations. (https://github.com/Automattic/WP-Job-Manager/issues/697)
* Fix - Changing the date of an expired job would forget the date, even though the job would become active. (https://github.com/Automattic/WP-Job-Manager/issues/653)
* Fix - Site owner can allow jobs to have only one or more than one types. (https://github.com/Automattic/WP-Job-Manager/issues/549)
* Fix - Show expired jobs if that setting is enabled. (https://github.com/Automattic/WP-Job-Manager/issues/703)
* Fix - Simplify the search message on the jobs page to avoid translation problems. (https://github.com/Automattic/WP-Job-Manager/issues/647)
* Fix - The uploader would ignore WordPress created image sizes. (https://github.com/Automattic/WP-Job-Manager/issues/706)
* Fix - setup.css was loaded on all admin pages. (https://github.com/Automattic/WP-Job-Manager/issues/728)
* Fix - The preview of a listing could be edited or viewed by anyone. Props @tripflex (https://github.com/Automattic/WP-Job-Manager/issues/690)
* Fix - When users were deleted their jobs weren't. (https://github.com/Automattic/WP-Job-Manager/issues/675)
* Fix - OrderBy Rand wasn't working. (https://github.com/Automattic/WP-Job-Manager/issues/714)
* Dev - Add upload filters and update PHPDocs, props @tripflex (https://github.com/Automattic/WP-Job-Manager/pull/747)
* Fix - Stop using jQuery.live, props @tripflex (https://github.com/Automattic/WP-Job-Manager/pull/664)

See additional changelog items in changelog.txt

## Upgrade Notice ##

### 1.25.3 ###
Make job types optional! Date format improvements! Update today!

=== Plugin Name ===
Book Doctor Appointments - iCliniq
Contributors: marshal@icliniq.com
Tags: Book Doctor Appointments, widget, sidebar, plugin 
Requires at least: 3.0
Tested up to: 3.4
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin uses https://www.icliniq.com 's doctor search API to list doctors in your website. Users can book doctor appointments from your blog


== Description ==
This plugin uses https://www.icliniq.com 's doctor search API to list doctors in your website. Users can book doctor appointments directly from your website. The plugin is very **flexible** and you can configure location and speciality for the doctors to be listed on your website.

To display the doctor listing anywhere in the code, the following method should be used

`<?php display_search_result_body($page, $results_per_page){ ?>`

where $page and $results_per_page are:

* **$page**           - page number of the search result; put 1 for the first page
* **$results_per_page** - number of listing per page

e.g: `<?php display_search_result_body(1, 10); ?>`

Find out more at http://icliniq.com/pages/display/page/wordpress-plugin


== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the folder `book-doctor-appointments-icliniq` to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to the Settings Options and configure it.

Find out more at http://icliniq.com/pages/display/page/wordpress-plugin


== Frequently Asked Questions ==

= What more this Plugin do for a website or a blog? =

This plugin uses https://www.icliniq.com 's doctor search API to list doctors in your website. Users can book doctor appointments directly from your website.

= What is icliniq.com =

htps://www.icliniq.com is an online doctor consultation platform. Users can ask a health query or consult a doctor online or book doctor appointments. This plugin facilitate a way to list these doctors in your website or blog.

== Screenshots ==

1. Doctot listing displayed as a sidebar widget


== Changelog ==

= 1.0 =
* Initial release.
* June 22th 2013.

== Upgrade Notice == 

Replace the existing files with the newer version
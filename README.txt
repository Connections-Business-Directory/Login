=== Connections Business Directory Login  ===
Contributors: shazahm1@hotmail.com
Donate link: http://connections-pro.com/
Stable tag: 2.0.3
Tags: address book, business directory, chamber of commerce, church directory, company directory, contact directory, directory, listings directory, local business directory, link directory, member directory, staff directory
Requires at least: 4.7.12
Tested up to: 5.2
Requires PHP: 5.6.20
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Extension for the Connections Business Directory that adds a shortcode and widget to display a login form.

== Description ==

This is an extension plugin for the [Connections Business Directory Plugin](http://wordpress.org/plugins/connections/) please be sure to install and active it before adding this plugin.

What does this plugin do?
It adds an [entry content block](http://connections-pro.com/documentation/login/#Content_Block), a [shortcode](http://connections-pro.com/documentation/login/#Shortcode) and a [highly configurable widget](http://connections-pro.com/documentation/login/#Widget) which displays a login form when a user is not logged into your site.

Ok, great, but how does this benefit me?
Well, if you have the directory setup to require login, you can add the [[connections_login] shortcode](http://connections-pro.com/documentation/login/#Shortcode) to the [login required message setting](http://connections-pro.com/documentation/settings/#Require_Login) (or any page you want, the shortcode is not limited to this setting). When it is added and the user is not logged in and visit your directory, they'll be shown your message plus the login form.

The content block login form and the login widget are best used with [Link](http://connections-pro.com/add-on/link/) installed and activated. You can setup the login form content block to be shown on a single entry, that way when a user visits the page and they are not logged in, they'll be shown a login form right on their page. Alternatively, you could use the widget which will only be displayed on the single entry page when a user is not logged in. It's your choice, you could use either one or both.

[Checkout the screenshots.](http://connections-pro.com/add-on/login/)

Here are some great **free extensions** (with more on the way) that enhance your experience with Connections Business Directory:

**Utility**

* [Toolbar](https://wordpress.org/plugins/connections-toolbar/) :: Provides quick links to the admin pages from the admin bar.

**Custom Fields**

* [Business Open Hours](https://wordpress.org/plugins/connections-business-directory-hours/) :: Add the business open hours.
* [Local Time](https://wordpress.org/plugins/connections-business-directory-local-time/) :: Add the business local time.
* [Facilities](https://wordpress.org/plugins/connections-business-directory-facilities/) :: Add the business facilities.
* [Income Level](https://wordpress.org/plugins/connections-business-directory-income-levels/) :: Add an income level.
* [Education Level](https://wordpress.org/plugins/connections-business-directory-education-levels/) :: Add an education level.
* [Languages](https://wordpress.org/plugins/connections-business-directory-languages/) :: Add languages spoken.
* [Hobbies](https://wordpress.org/plugins/connections-business-directory-hobbies/) :: Add hobbies.

**Misc**

* [Face Detect](https://wordpress.org/plugins/connections-business-directory-face-detect/) :: Applies face detection before cropping an image.

**[Premium Extensions](https://connections-pro.com/extensions/)**

* [Authored](https://connections-pro.com/add-on/authored/) :: Displays a list of blog posts written by the entry on their profile page.
* [Contact](https://connections-pro.com/add-on/contact/) :: Displays a contact form on the entry's profile page to allow your visitors to contact the entry without revealing their email address.
* [CSV Import](https://connections-pro.com/add-on/csv-import/) :: Bulk import your data in to your directory.
* [Custom Category Order](https://connections-pro.com/add-on/custom-category-order/) :: Order your categories exactly as you need them.
* [Custom Entry Order](https://connections-pro.com/add-on/custom-entry-order/) :: Allows you to easily define the order that your business directory entries should be displayed.
* [Enhanced Categories](https://connections-pro.com/add-on/enhanced-categories/) :: Adds many features to the categories.
* [Form](https://connections-pro.com/add-on/form/) :: Allow site visitor to submit entries to your directory. Also provides frontend editing support.
* [Link](https://connections-pro.com/add-on/link/) :: Links a WordPress user to an entry so that user can maintain their entry with or without moderation.
* [ROT13 Encryption](https://connections-pro.com/add-on/rot13-email-encryption/) :: Protect email addresses from being harvested from your business directory by spam bots.
* [SiteShot](https://connections-pro.com/add-on/siteshot/) :: Show a screen capture of the entry's website.
* [Widget Pack](https://connections-pro.com/add-on/widget-pack/) :: A set of feature rich, versatile and highly configurable widgets that can be used to enhance your directory.

== Installation ==

= Using the WordPress Plugin Search =

1. Navigate to the `Add New` sub-page under the Plugins admin page.
2. Search for `connections business directory login`.
3. The plugin should be listed first in the search results.
4. Click the `Install Now` link.
5. Lastly click the `Activate Plugin` link to activate the plugin.

= Uploading in WordPress Admin =

1. [Download the plugin zip file](http://wordpress.org/plugins/connections-business-directory-login/) and save it to your computer.
2. Navigate to the `Add New` sub-page under the Plugins admin page.
3. Click the `Upload` link.
4. Select Connections Business Directory Login zip file from where you saved the zip file on your computer.
5. Click the `Install Now` button.
6. Lastly click the `Activate Plugin` link to activate the plugin.

= Using FTP =

1. [Download the plugin zip file](http://wordpress.org/plugins/connections-business-directory-login/) and save it to your computer.
2. Extract the Connections Business Directory Login zip file.
3. Create a new directory named `connections-business-directory-login` directory in the `../wp-content/plugins/` directory.
4. Upload the files from the folder extracted in Step 2.
4. Activate the plugin on the Plugins admin page.

== Frequently Asked Questions ==

None yet...

== Screenshots ==

[Screenshots can be found here.](http://connections-pro.com/add-on/login/)

== Changelog ==

= 2.0.3 06/05/2018 =
* BUG: Shortcode returns content, not echo it.
* DEV: phpDoc update.

= 2.0.2 12/14/2017 =
* BUG: Prevent PHP warning; "Illegal string offset 'echo'".

= 2.0.1 03/17/2016 =
* NEW: Introduce the `cn_login_widget_link_anchor` filter.
* BUG: Use correct bbPress function to return the user topics created URL.
* TWEAK: Default logout link redirect URL to the current page.
* OTHER: Correct version number in changelog section of readme.txt.

= 2.0 03/02/2016 =
* FEATURE: Option to configure widget to be visible site wide in the sidebar or limited to only the entry detail/profile page in Connections.
* FEATURE: Configurable widget title based on if user is logged in or not.
* FEATURE: Option to disable the "Remember me" checkbox in the login form.
* FEATURE: Option to disable the "Lost Password" link in the login form.
* FEATURE: Add support for adding custom links which can be displayed to a logged out user.
* FEATURE: Option to display the users Gravatar when they are logged in.
* FEATURE: Option to set the Gravatar's image size.
* FEATURE: Option to display the user's admin profile link.
* FEATURE: Option to display the logout link.
* FEATURE: Add support for adding custom links which can be displayed to a logged in user.
* FEATURE: Support for bbPress.
* FEATURE: Support for BuddyPress.
* FEATURE: Extension support and integration with the [Link extension](http://connections-pro.com/add-on/link/).
* FEATURE: Add shortcode options to the [[connections_login] shortcode](http://connections-pro.com/documentation/login/#Shortcode) so the labels can be configured.
* NEW: Introduce the `cn_login_supported_tokens` filter.
* NEW: Introduce the `cn_login_avatar_size` filter.
* NEW: Introduce the `cn_login_logout_url` filter.
* NEW: Introduce the `cn_login_login_url` filter.
* NEW: Introduce the `cn_login_replace_tokens` filter.
* NEW: Introduce the `cn_login_image_types` filter.
* NEW: Introduce the `cn_login_widget_update_settings` filter.
* NEW: Introduce the `cn_login_before_widget_common_settings` action.
* NEW: Introduce the `cn_login_after_widget_common_settings` action.
* NEW: Introduce the `cn_login_before_widget_logged_out_settings` action.
* NEW: Introduce the `cn_login_after_widget_logged_out_settings` action.
* NEW: Introduce the `cn_login_after_widget_logged_in_settings` action.
* NEW: Introduce the `cn_login_widget_before` action.
* NEW: Introduce the `cn_login_widget_logged_in_before` action.
* NEW: Introduce the `cn_login_widget_logged_in_after` action.
* NEW: Introduce the `cn_login_widget_logged_out_before` action.
* NEW: Introduce the `cn_login_widget_logged_out_after` action.
* NEW: Introduce the `cn_login_widget_after` action.
* NEW: Introduce the `cn_login_display_image_{$type}` action.
* NEW: Introduce the `cn_login_widget_lost_password_url` filter.
* NEW: Introduce the `cn_login_widget_register_url` filter.
* NEW: Introduce the `cn_login_widget_register_url` action.
* NEW: Introduce the `cn_login_widget_{$context}_links` filter.
* NEW: Introduce the `cn_login_widget_before_{$context}_links` action.
* NEW: Introduce the `cn_login_widget_after_{$context}_links` action.
* TWEAK: Escape translated strings.
* I18N: Update POT file.
* I18N: Update es_ES PO/MO files.

= 1.1 07/06/2015 =
* BUG: Load the text domain immediately on plugins_loaded action so the translation files will be loaded.
* BUG: Remove stray period from version number.
* TWEAK: Refactor loadTextDomain() so it is consistent with the other extensions for Connections.
* I18N: Include the POT file.
* I18N: Add a Spanish (Spain) translation (machine translated).
* DEV: Update .gitignore.

= 1.0 08/08/2014 =
* Initial release.

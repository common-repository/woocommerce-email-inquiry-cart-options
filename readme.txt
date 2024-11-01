=== Email Inquiry & Cart Options for WooCommerce ===
Contributors: a3rev, nguyencongtuan
Tags: WooCommerce, WooCommerce Email Inquiry, WooCommerce Catalog Visibility, WooCommerce add to cart, WooCommerce Brochure Page, WooCommerce product Emails
Requires at least: 6.0
Tested up to: 6.6
Stable tag: 3.4.1
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Set Product Page Rules, Hide Add to Cart, Hide Price, Show Email Inquiry, Filter Rules by Roles for logged in users. 100% Mobile responsive Email Inquiry form!

== Description ==

Email Inquiry & Cart Options for WooCommerce allows you to fine tune the e-commerce accessibility on your WooCommerce site by setting 'Rules' that apply to all site visitors. Fine tune access to the e-commerce function for logged in users by assigning the Rules to WordPress user roles, including the WooCommerce Customer and Store manager Roles.

Add a space saving and impressive pop-up email inquiry form to your product offering. Pop-up Email Inquiry form is 100% mobile responsive and displays the form beautifully in any mobile in portrait or landscape.

= Catalog Visibility Rules =

* Rule: Hide 'Hide Product Prices'
	- Apply Rule to all not logged in users
	- Filter Rule by user role for logged in users.
* Rule: Hide 'Add to Cart'
	- Apply Rule to all not logged in users
	- Filter Rule by user role for logged in users.
* Rule: Show Email Inquiry Button
	- Apply Rule to all logged in users.
	- Filter Rule by user Role for logged in users.

=  Apply Rules to Roles =

Fine tune your entire Catalog visibility by
* 'Apply Rules to Roles' - Configure which user roles each Rule is to Apply too. Fine grained control over what your account holders can see and access once they are logged into your site.

= Email Product Inquiry Form =

Email Inquiry & Cart Options uses the WordPress email config and requires no external email plugin. Features

* Instantly adds a Product Email Inquiry button to every product page.
* Option to use hyperlinked text instead of a Button.
* Email Inquiry form is a pop up form. 
* Fully mobile responsive pop up form
* Set pop up styles from the plugins settings
* Set the receiver email address.
* Set a receiver cc email address
* Name field has option to turn ON or OFF *Required field
* Telephone Field has ON or OFF option to show. 
* Telephone Field IF showing has option for *Required field ON or OFF  
* Fully customizable Sent success message shows on a pop-up after inquiry is submitted.
* Use the WordPress text editor (WYSIWYG and HTML) to style the success message (see image under the Screenshots tab on this page).
* **NEW** Email Inquiry shortcodes. Works with New WC Single Product Page Bock Template and page builders like Elementor.

= Compatibility =

All the features of Email Inquiry & Cart Options for WooCommerce including Hide Price, Hide the Cart and Email Inquiry   work with these official WooCommerce plugins.

* WooCommerce Addons Plugin
* WooCommerce Product Bundles Plugin

= GDPR Compliant =

The plugins email contact form has options to turn on GDPR compliance features. They include:

* EU GDPR law complaint email form with option to turn it ON or OFF if not required
* Option to include Privacy Policy Statement with link to privacy Page.
* When on shows Terms and conditions acceptance checkbox on form with Dynamic text.

= Templating =

If you are a coder and wish to add your own style (that can�t be added from the plugins settings) the plugin supports template over rides. Copy any template file into your theme and apply custom CSS from there.

= Premium Upgrade & Support =

Please be aware that whilst we upgrade this plugin regularly time does not permit us to monitor the support forum and provide active support for the Email Inquiry and Cart Options for WooCommerce Free version. 

Premium support and some nice advanced features are available with the [Email Inquiry Ultimate](https://a3rev.com/shop/woocommerce-email-inquiry-ultimate/) Premium version upgrade.

= Contribute =

If you�re interested in contributing to Email Inquiry & Cart Options for WooCommerce head over to the plugins [GitHub Repository](https://github.com/a3rev/woocommerce-email-inquiry-cart-options-lite) to find out how you can pitch in.

Want to add a new language translation? Great! You can contribute via [translate.wordpress.org.](https://translate.wordpress.org/projects/wp-plugins/woocommerce-email-inquiry-cart-options)

== Installation ==

= Minimum Requirements =

* PHP version 7.4 or greater is recommended
* MySQL version 5.6 or greater is recommended

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't even need to leave your web browser. To do an automatic install of Email Inquiry & Cart Options for WooCommerce, log in to your WordPress admin panel, navigate to the Plugins menu and click Add New.

In the search field type "Email Inquiry & Cart Options for WooCommerce" and click Search Plugins. Once you have found our plugin you can install it by simply clicking Install Now. After clicking that link you will be asked if you are sure you want to install the plugin. Click yes and WordPress will automatically complete the installation.

= Manual installation =

The manual installation method involves downloading our plugin and uploading it to your web server via your favourite FTP application.

1. Download the plugin file to your computer and unzip it
2. Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installations wp-content/plugins/ directory.
3. Activate the plugin from the Plugins menu within the WordPress admin.


== Screenshots ==

1. Transform your WooCommerce store into a brochure site with email inquiry pop up for front end users.
2. Set Rules that apply to all front end users and then select user Roles that the Rule is to apply to.
3. The on page Email pop-up form
4. The on page Email sent success message also shows in the pop up.
5. Use the WordPress text editor to fully customize your success message.

== Usage ==

1. Install and activate the plugin

2. Email & Cart Options

3. Set Product Page Rules and assign to Roles.

4. Click on the Email Inquiry tab and configure your email inquiry button and success message.

5. Have fun.

== Frequently Asked Questions ==

= When can I use this plugin? =

You can use this plugin only when you have installed the WooCommerce plugin.


== Changelog ==

= 3.4.1 - 2024/07/13 =
* This release has various tweaks for compatibility with WordPress 6.6 and WooCommerce 8.9.3.
* Tweak - Tested for compatibility with WordPress 6.6
* Tweak - Tested for compatibility with WooCommerce 8.9.3

= 3.4.0 - 2023/11/27 =
* This feature release adds auto fill name and email on default form for logged in users.
* Feature - Default Email Form, auto fill Name and Email of current logged in user. Saves logged in user from having complete those fields.

= 3.3.2 - 2023/11/22 =
* This maintenance release has plugin framework updates for compatibility with PHP 8.1 onwards, plus backward compatibility to WooCommerce 6.0.
* Tweak - Remove backward compatibility for WooCommerce versions less than 6.0
* Framework - Set parameter number of preg_match function from null to 0 for compatibility with PHP 8.1 onwards
* Framework - Validate empty before call trim for option value

= 3.3.1 - 2023/10/30 =
* This maintenance release has a Code Tweak for compatibility with WordPress 6.4 and WooCommerce 8.2
* Tweak - Tested for compatibility with WordPress 6.4
* Tweak - Tested for compatibility with WooCommerce 8.2
* Tweak - Call add action to 'enqueue_block_assets' instead of 'enqueue_block_editor_assets' for enqueue style inside iframe of Gutenberg.

= 3.3.0 - 2023/09/07 =
* This feature release adds a "Product Inquiry Button" Block for use in Gutenberg Templates. Also compatibility with WooCommerce 8.0.3 and WordPress 6.3
* Feature - Define new "Product Inquiry Button" block to show Inquire Button on Gutenberg Block templates.
* Tweak - Test for compatibility with WooCommerce 8.0.3
* Tweak - Test for compatibility with WordPress 6.3.0
* Fix - New "Product Inquiry Button" Block resolves issues that the Email Inquiry shortcode has with Gutenberg templates.

= 3.2.2 - 2023/07/28 =
* This maintenance release has 2 bug fixes for compatibility with WooCommerce 7.9 and WordPress 6.2.2 or higher.
* Tweak - Test for compatibility with WooCommerce 7.9.0
* Tweak - Test for compatibility with WordPress 6.2.2
* Fix - validate if $product is WC_Product or not before call get_id() . For compatibility with WC 7.9.0
* Fix - Show correct Inquiry button for each product inside query loop from Gutenberg template with double [[ ]] for compatibility with WP 6.2.2 or higher.

= 3.2.1 - 2023/06/26 =
* This maintenance release fixes a small PHP bug that emerged from the 3.2.0 release.
* Fix - defined wc_email_inquiry_button_position variable on correct position to fix PHP bug

= 3.2.0 - 2023/06/22 =
* This feature release adds insert Email Inquiry by 2 new shortcodes. Works with New WC Single Product Page Bock Template and page builders like Elementor.
* Feature - Add Email Inquiry Shop shortcode. Adds Email Inquiry to all product pages across the store.
* Feature - Add Single Product Email Inquiry shortcode. Use to insert a Single Product Email Inquiry, by product id into anywhere that accepts shortcodes.
* Feature - Fully compatible with the new WooCommerce Single Product Blocks Template
* Feature - Fully compatible with page builders like Elementor, Divi etc
* Tweak - Adds new Email Inquiry Shortcode options to the Settings tab
* Tweak - Test for compatibility with WooCommerce 7.8.0

= 3.1.0 - 2023/04/25 =
* This release has compatibility with WordPress 6.2.0, WooCommerce 7.6.0 plus declared compatibility with WooCommerce HPOS.
* Tweak - Test for compatibility with WordPress 6.2
* Tweak - Test for compatibility with WooCommerce 7.6.0
* Tweak - Test and declare plugin compatibility with WooCommerce HPOS Custom Tables.

= 3.0.0 - 2023/01/03 =
* This feature release removes the fontawesome lib and replaces icons with SVGs plus adds Default Topography option to font controls and has compatibility with WooCommerce 7.2
* Feature - Convert icon from font awesome to SVG
* Feature - Update styling for new SVG icons
* Tweak - Test for compatibility with WooCommerce 7.2
* Plugin Framework - Update typography control from plugin framework to add support for Default value
* Plugin Framework - Default value will get fonts set in the theme.
* Plugin Framework - Change generate typography style for change on typography control
* Plugin Framework - Remove fontawesome lib

= 2.9.0 - 2022/12/06 =
* This feature release adds Default font from the theme to the font control.
* Feature - Add Default fonts from the Theme to the font control options.
* Feature - On new install will get the theme fonts with Arial web font fall back.
* Feature - On existing installs this update will not change the set fonts.
* Plugin Framework - Update typography control from plugin framework to add support for Default value
* Plugin Framework - Default value will get the h tag and content fonts that are set in the theme.
* Plugin Framework - Change generate typography style for change on typography control

= 2.8.2 - 2022/11/21 =
* This maintenance release has 1 bug fix and compatibility with WooCommerce 7.1
* Tweak - Check for compatibility with WooCommerce version 7.1 
* Fix - Show the panel settings page if have combine of premium and free options on same page.

= 2.8.1 - 2022/11/01 =
* This maintenance release has a security vulnerability patch, plus compatibility with WordPress major version 6.1.0 and WooCommerce version 7.0
* Tweak - Test for compatibility with WordPress 6.1
* Tweak - Test for compatibility with WooCommerce 7.0
* Security - This release has a patch for a security vulnerability

= 2.8.0 - 2022/05/24 =
* This release is for compatibility with WordPress major version 6.0 and WooCommerce version 6.5.1. It and includes various code tweaks and tweaks to harden security.
* Tweak - Test for compatibility with WordPress 6.0
* Tweak - Add filter on generate_border_style_css
* Tweak - Add filter on generate_border_corner_css
* Tweak - Test for compatibility with WooCommerce 6.5
* Framework � Upgrade Plugin Framework to version 2.6.0
* Security - Various code hardening tweaks.
* Security - Escape all $-variable
* Security - Sanitize all $_REQUEST, $_GET, $_POST
* Security - Apply wp_unslash before sanitize

= 2.7.0 - 2022/01/22 =
* This release has a new Google Fonts API Validation feature plus compatibility with WordPress 5.9 and WooCommerce 6.1.1
* Feature - Add Ajax Validate button for Google Fonts API, for quick and easy Validation of API key.
* Dev - Add dynamic help text to Google Font API field
* Tweak - Test for compatibility with WooCommerce 6.1
* Tweak - Test for compatibility with WordPress 5.9
* Framework - Update a3rev Plugin Framework to version 2.5.0

= 2.6.3 - 2021/11/20 =
* This maintenance release has fixes for compatibility with PHP version 8.x
* Tweak - Test for compatibility with PHP 8.x
* Fix - Update some defined functions without an optional parameter when followed by a required parameter. This is deprecated as of PHP 8.0.0

= 2.6.2 - 2021/11/10 =
* This maintenance release has a compatibility bug fix for WooCommerce version 5.9.0 compatibility
* Tweak - Test for compatibility with WooCommerce 5.9
* Fix - Checked if $product variable is WC_Product for compatibility with WC 5.9

= 2.6.1 - 2021/11/09 =
* This maintenance release has a PHP fatal Error fix that has arisen out of yesterdays version 2.6.0 feature release.
* Fix - Validate the global $product variable for call is_type() to check bundle product type.

= 2.6.0 - 2021/11/08 =
* This feature release adds compatibility with the WooCommerce Product Bundles plugin
* Feature - Add full Email Inquiry button and hide price and cart compatibility with the official WooCommerce Product Bundles plugin

= 2.5.1 - 2021/08/12 =
* This maintenance release completes full compatibility with The WooCommerce Products Add-on plugin.
* Fix - Hide price of addon items in the content section where the WooCommerce Product Add-ons plugin shows price in the description.
* Fix - Show price of add-ons from Edit Order so admin can see the price in the order.

= 2.5.0 - 2021/08/07 =
* This feature release adds full compatibility with WooCommerce Product Add-ons
* Feature - Write new filter to add support for hiding WooCommerce Product Addons prices on when the Hide Price is actived.

= 2.4.11 - 2021/07/22 =
* This maintenance release has code tweaks for compatibility with WordPress Major version 5.8, WooCommerce version 5.5.1 and some Security Hardening.
* Tweak - Test for compatibility with WordPress 5.8
* Tweak - Test for compatibility with WooCommerce 5.5.1
* Tweak - Skip version 2.4.10 to avoid PHP misread of the version number
* Security - Add more variable, options and html escaping

= 2.4.9 - 2021/03/19 =
* This maintenance release updates 23 deprecated jQuery functions for compatibility with the latest version of jQuery in WordPress 5.7
* Tweak - Update JavaScript on plugin framework for compatibility with latest version of jQuery and resolve PHP warning event shorthand is deprecated.
* Tweak - Replace deprecated .change( handler ) with .on( 'change', handler )
* Tweak - Replace deprecated .change() with .trigger('change')
* Tweak - Replace deprecated .focus( handler ) with .on( 'focus', handler )
* Tweak - Replace deprecated .focus() with .trigger('focus')
* Tweak - Replace deprecated .click( handler ) with .on( 'click', handler )
* Tweak - Replace deprecated .click() with .trigger('click')
* Tweak - Replace deprecated .select( handler ) with .on( 'select', handler )
* Tweak - Replace deprecated .select() with .trigger('select')
* Tweak - Replace deprecated .blur( handler ) with .on( 'blur', handler )
* Tweak - Replace deprecated .blur() with .trigger('blur')
* Tweak - Replace deprecated .resize( handler ) with .on( 'resize', handler )
* Tweak - Replace deprecated .submit( handler ) with .on( 'submit', handler )
* Tweak - Replace deprecated .scroll( handler ) with .on( 'scroll', handler )
* Tweak - Replace deprecated .mousedown( handler ) with .on( 'mousedown', handler )
* Tweak - Replace deprecated .mouseover( handler ) with .on( 'mouseover', handler )
* Tweak - Replace deprecated .mouseout( handler ) with .on( 'mouseout', handler )
* Tweak - Replace deprecated .keydown( handler ) with .on( 'keydown', handler )
* Tweak - Replace deprecated .attr('disabled', 'disabled') with .prop('disabled', true)
* Tweak - Replace deprecated .removeAttr('disabled') with .prop('disabled', false)
* Tweak - Replace deprecated .attr('selected', 'selected') with .prop('selected', true)
* Tweak - Replace deprecated .removeAttr('selected') with .prop('selected', false)
* Tweak - Replace deprecated .attr('checked', 'checked') with .prop('checked', true)
* Tweak - Replace deprecated .removeAttr('checked') with .prop('checked', false)

= 2.4.8 - 2021/03/09 =
* This maintenance release is for compatibility with WordPress 5.7 and WooCommerce 5.1
* Tweak - Test for compatibility with WordPress 5.7
* Tweak - Test for compatibility with WooCommerce 5.1.0

= 2.4.7 - 2021/01/13 =
* This maintenance release is for compatibility with WooCommerce major version 4.9.0.
* Tweak - Test for compatibility with WooCommerce 4.9.0

= 2.4.6 - 2020/12/30 =
* This is an important maintenance release that updates our scripts for compatibility with the latest version of jQuery released in WordPress 5.6
* Tweak - Update JavaScript on plugin framework for work compatibility with latest version of jQuery
* Fix - Replace .bind( event, handler ) by .on( event, handler ) for compatibility with latest version of jQuery
* Fix - Replace :eq() Selector by .eq() for compatibility with latest version of jQuery
* Fix - Replace .error() by .on( �error� ) for compatibility with latest version of jQuery
* Fix - Replace :first Selector by .first() for compatibility with latest version of jQuery
* Fix - Replace :gt(0) Selector by .slice(1) for compatibility with latest version of jQuery
* Fix - Remove jQuery.browser for compatibility with latest version of jQuery
* Fix - Replace jQuery.isArray() by Array.isArray() for compatibility with latest version of jQuery
* Fix - Replace jQuery.isFunction(x) by typeof x === �function� for compatibility with latest version of jQuery
* Fix - Replace jQuery.isNumeric(x) by typeof x === �number� for compatibility with latest version of jQuery
* Fix - Replace jQuery.now() by Date.now() for compatibility with latest version of jQuery
* Fix - Replace jQuery.parseJSON() by JSON.parse() for compatibility with latest version of jQuery
* Fix - Remove jQuery.support for compatibility with latest version of jQuery
* Fix - Replace jQuery.trim(x) by x.trim() for compatibility with latest version of jQuery
* Fix - Replace jQuery.type(x) by typeof x for compatibility with latest version of jQuery
* Fix - Replace .load( handler ) by .on( �load�, handler ) for compatibility with latest version of jQuery
* Fix - Replace .size() by .length for compatibility with latest version of jQuery
* Fix - Replace .unbind( event ) by .off( event ) for compatibility with latest version of jQuery
* Fix - Replace .unload( handler ) by .on( �unload�, handler ) for compatibility with latest version of jQuery

= 2.4.5 - 2020/12/10 =
* Tweak - Test for compatibility with WooCommerce 4.8.0

= 2.4.4 - 2020/12/08 =
* This maintenance release has tweaks and a fix for compatibility with WordPress major version 5.6, WooCommerce 4.7.1 and PHP 7.4.8
* Tweak - Test for compatibility with PHP 7.4.8
* Tweak - Test for compatibility with WooCommerce 4.7.1
* Tweak - Test for compatibility with WordPress 5.6
* Fix - Add \ before WC() inside namespace file for it to call to correct WC() of WooCommerce 

= 2.4.3 - 2020/08/08 =
* This maintenance release is for compatibility with WordPress major version 5.5 and WooCommerce 4.3.1.
* Tweak - Test for compatibility with WordPress 5.5
* Tweak - Test for compatibility with WooCommerce 4.3.1

= 2.4.2 - 2020/05/05 =
* This maintenance release removes form modal popup h tags plus has compatibility with WooCommerce 4.1.0
* Tweak - Change h2 and h5 title font on modal popup to div tag so that they don't show up as empty h tags with Search engine crawl.
* Tweak - Tested for compatibility with WooCommerce 4.1.0
* Tweak - Update WooCommerce compatibility tag

= 2.4.1 - 2020/03/28 =
* This maintenance release is for compatibility with WordPress 5.4, WooCommerce 4.0.1, Travis CI build unit test for compliance with WordPress PHP coding standards and PHP tweaks for compatibility with PHP v 7.0 to 7.4 
* Tweak - Test for compatibility with WordPress 5.4
* Tweak - Test for compatibility with WooCommerce 4.0.1
* Tweak - Run Travis CI unit build tests for PHP compatibility issues with PHP 7.0 to 7.4
* Fix - Update global ${$this- to $GLOBALS[$this to resolve 7.0+ PHP warnings
* Fix - Update global ${$option} to $GLOBALS[$option] to resolve 7.0+ PHP warnings
* Fix - Update less PHP lib that use square brackets [] instead of curly braces {} for Array, depreciated in PHP 7.4
* Fix - Validate for do not use get_magic_quotes_gpc function for PHP 7.4

= 2.4.0 - 2020/01/16 =
* This feature release completes the full refactor (frontend and backend) of the plugins PHP to Composer plus compatibility with WordPress 5.3.2 and WooCommerce 3.8.1
* Feature - Plugin Framework fully refactored to Composer for cleaner code and faster PHP code on the admin panels
* Tweak - Update plugin for compatibility with new version of plugin Framework
* Tweak - Test for compatibility with WordPress 5.3.2
* Tweak - Test for compatibility with WooCommerce 3.8.1

= 2.3.0 - 2019/11/13 =
* This feature release has a lot including compatibility with WooCommerce 3.8.0, WordPress 5.3 whilst maintaining backward compatibility, PHP upgrade to Composer PHP Dependency Manger and a full security review and update.
* Feature - Plugin fully refactored to Composer for cleaner code and faster PHP code
* Tweak - Test for compatibility with WordPress 5.3.0
* Tweak - Test for compatibility with WooCommerce 3.8.0
* Tweak - Remove the hard coded PHP error_reporting display errors false from compile sass to css
* Tweak - Update templates use new namespace
* Tweak - Support for backward compatibility for the theme have override with old template
* Dev - Replace file_get_contents with HTTP API wp_remote_get
* Dev - Ensure that all inputs are sanitized and all outputs are escaped.

= 2.2.5 - 2019/09/25 =
* Maintenance upgrade to add support for Hide Add to Cart on product cards added by WooCommerce Gutenberg block.
* Tweaks - Add hook to hide Add to Cart on products inserted by WooCommerce Product Grid Block
* Tweak - Test for compatibility with WooCommerce 3.7.0

= 2.2.4 - 2019/06/29 =
* This is a maintenance upgrade to fix a potentially fatal error conflict with sites running PHP 7.3 plus compatibility with WordPress v 5.2.2 and WooCommerce 3.6.4
* Tweak - Test for compatibility with WooCommerce 3.6.4
* Tweak - Test for compatibility with WordPress 5.2.2
* Fix - PHP warning continue targeting switch is equivalent to break for compatibility on PHP 7.3

= 2.2.3 - 2019/04/26 =
* This maintenance update has tweaks for compatibility with WordPress 5.2.0 and WooCommerce 3.6.0 major new versions whilst maintaining backward compatibility
* Tweak - Test for compatibility with WordPress 5.2.0
* Tweak - Test for compatibility with WooCommerce 3.6.2
* Tweak - Support for backward compatibility with WooCommerce v 3.5

= 2.2.2 - 2019/04/01 =
* This maintenance upgrade fixes an issue with Variation Price and description display when add to cart is hidden plus compatibility with WooCommerce 3.5.7 and upcoming WordPress 5.2
* Tweak - Test for compatibility with WordPress 5.2
* Tweak - Test for compatibility with WooCommerce 3.5.7
* Fix - don't add duplicate price and description for Product Variation, fix for work compatibility with WooCommerce version 3.5 +

= 2.2.1 - 2018/12/24 =
* This maintenance update is for compatibility with WordPress 5.0.2, WooCommerce 3.5.3 and PHP 7.3. It also includes performance updates to the plugin framework.
* Tweak - Editor sidebar global Email & Cart meta box works with both Gutenberg and Classic Editor
* Tweak - Test for compatibility with WordPress 5.0.2 and WordPress 4.9.9
* Tweak - Test for compatibility with WooCommerce 3.5.3
* Tweak - Create new structure for future development of Gutenberg Blocks
* Framework - Performance improvement.  Replace wp_remote_fopen  with file_get_contents for get web fonts
* Framework - Performance improvement. Define new variable `is_load_google_fonts` if admin does not require to load google fonts
* Credit - Props to Derek for alerting us to the framework google fonts performance issue
* Framework - Register style name for dynamic style of plugin for use with Gutenberg block
* Framework - Update Modal script and style to version 4.1.1
* Framework - Update a3rev Plugin Framework to version 2.1.0
* Framework - Test and update for compatibility with PHP 7.3

= 2.2.0 - 2018/07/23 =
* This feature upgrade gives options between show email inquiry on frontend as a Button or Hyperlink text with full style options plus compatibility with WordPress 4.9.7
* Feature - Added the option to show email inquiry as a Button or a Hyperlinked text on product cards and product pages.
* Feature - Added Full Button Style setting options to style the button to match the theme
* Feature - Added conditional logic to menu, when select Button the Button style options show, when select hyperlink those options show
* Feature - Added Button margin settings for tweaking the alignment of the button
* Feature - Added Hyperlink Font editor with margin settings for alignment
* Feature - Added Hyperlink Dynamic Text editor, with Before linked text and After Link text options
* Tweak - Added new menu on Email Inquiry Tab as a sub menu Email Button Style  
* Tweak - Test for compatibility with WordPress 4.9.7

= 2.1.0 - 2018/07/09 =
* This Feature Upgrade adds a new Product Page Rule, Hide Product Price plus full compatibility with WooCommerce Quotes and Orders major version 3.0.0, WooCommerce On Page Checkout and WooCommerce 3.4.3
* Feature - Add new Product Page Rule Hide Product Price
* Feature - Define new hooks and filters for compatibility with WooCommerce Quotes & Orders plugin
* Tweak - Add new hooks and functions for full compatibility with WooCommerce On Page Checkout plugin
* Tweak - Move and Update Help Notes from the Plugin Framework Global Settings option box to new option box called Help Notes 
* Tweak - Update plugins description in readme file.
* Tweak - Various plugins option boxes text changes and additions
* Framework - Convert old tooltip script to bootstrap tooltip
* Tweak - Test for compatibility with WooCommerce 3.4.3
* Framework - Update a3rev Plugin Framework to version 2.0.6

= 2.0.1 - 2018/06/19 =
* Maintenance update fixes a bug with email inquiry showing under footer on some sites plus a tweak to the modal pop up in mobile and fix on framework setting options.
* Tweak - Auto scroll to top of modal popup when it opens for improved UI on mobile
* Framework - Fix for Framework Global Box open and close settings options  
* Framework - Update a3rev Plugin Framework to version 2.0.5
* Fix - Issue where Email Inquiry form was loading at footer of page on some sites

= 2.0.0 - 2018/06/14 =
* Major Upgrade. V2 is a massive step forward in the plugins development with 11 new features, new pop up tool and big code refactoring.
* Feature - Introducing new Bootstrap Modal pop up for email inquiry form
* Feature - Refactored plugin style with introduction of Templating
* Feature - Email Form. Added Sender Request a Copy option
* Feature - Email Form. Added Email Form Background Colour style feature 
* Feature - Email Form. Added Default Form Fonts and Text style options
* Feature - Email Form. Added Default Form Text Input Fields style options 
* Feature - Email Form. Added Default Form SEND Button Style options
* Feature - Email Form. Added Form Field Options box
* Feature - Name field has option to turn ON or OFF Required field
* Feature - Telephone field has ON or OFF option to show. 
* Feature - Telephone field IF showing has option for Required field ON or OFF
* Feature - Message Field has option to turn ON or OFF Required field
* Tweak - Remove Fancybox and Colorbox pop up tools
* Tweak - Remove Popup Tool settings box
* Tweak - Remove plugin admin page sidebar Place card for discontinued Pro version plugin.
* Tweak - Updated the plugins readme file to reflect the many changes in this version
* Tweak - Multiple coding standard enhancements.
* Tweak - Test for compatibility with WooCommerce 3.4.2
* Refactor - Inline script to Templating to allow developers to over ride default styles by copying any template into their theme and styling it from there.
* Template - Create new template file email-inquiry/default-form.php. 
* Template - Create new template file email-inquiry/modal-popup.php
* Template - Create new template file email-inquiry/email-notification.php. 
* Framework - Update Modal script and style to version 4.1.1
* Framework - Update a3rev Plugin Framework to version 2.0.4

= 1.4.8 - 2018/05/26 =
* This maintenance update is for compatibility with WordPress 4.9.6 and WooCommerce 3.4.0 and the new GDPR compliance requirements for users in the EU 
* Tweak - Default Email Inquiry Form. Add new GDPR Compliance Options Box with option to turn Acceptance notice ON or OFF for default form.
* Tweak - When Acceptance notice is ON option shows to edit the default text that shows to the right of the acceptance box. 
* Tweak - When Acceptance Notice is ON option shows to add information text to the bottom of the form. Leave the text edit empty on and nothing shows on the form footer.
* Framework - Update a3rev Plugin Framework to version 2.0.3
* Tweak - Test for compatibility with WooCommerce 3.4.0
* Tweak - Test for compatibility with WordPress 4.9.6

= 1.4.7 - 2018/02/13 =
* Maintenance Update. Under the bonnet tweaks to keep your plugin running smoothly and is the foundation for new features to be developed this year 
* Framework - Update a3rev Plugin Framework to version 2.0.2
* Framework - Add Framework version for all style and script files
* Tweak - Update for full compatibility with a3rev Dashboard plugin
* Tweak - Test for compatibility with WordPress 4.9.4
* Tweak - Test for compatibility with WooCommerce 3.3.1

= 1.4.6 - 2017/10/13 =
* Tweak - Tested for compatibility with WooCommerce 3.2.0
* Tweak - Tested for compatibility with WordPress 4.8.2
* Tweak - Added support for the new WC 'tested up to' feature to show this plugin has been tested compatible with WC updates

= 1.4.5 - 2017-06-06 =
* Tweak - Tested for compatibility with WordPress major version 4.8.0
* Tweak - tested for compatibility with WooCommerce version 3.0.7
* Tweak - Include bootstrap modal script into plugin framework
* Tweak - Update a3rev plugin framework to latest version

= 1.4.4 - 2017/04/13 =
* Tweak - Full compatibility with WC version 3.0.2 with full backward compatibility to WC version 2.6.0
* Tweak - Change call direct to Product properties with new function that are defined on WC v3.0
* Tweak - Change call direct to Order properties with new function that are defined on WC v3.0
* Tweak - Called action for save data of plugin after WC data is saved on new CRUD
* Tweak - Change priority for save_post action so that it is called after WooCommerce save the product data, to get the correct data on WC v3.0
* Tweak - Change global $$variable to global ${$variable} for compatibility with PHP 7.0
* Tweak - Update a3 Revolution to a3rev Software on plugins description
* Tweak - Added Settings link to plugins description on plugins menu
* Tweak - Update plugins WordPress page banner image to new format size 1550px by 500px
* Tweak - Tested for full compatibility with WordPress version 4.7.3

= 1.4.3 - 2016/10/26 = 
* Tweak - Hardcode Fancybox and Colorbox pop-up Scroll with page option on mobiles for improved UX
* Tweak - Define new 'Ajax Multi Submit' control type with Progress Bar showing and Statistic for plugin framework
* Tweak - Define new 'Ajax Submit' control type with Progress Bar showing for plugin framework
* Tweak - Update plugin framework styles and scripts support for new 'Ajax Submit'and 'Ajax Multi Submit' control type
* Tweak - Tested for full compatibility with WooCommerce version 2.6.6

= 1.4.2 - 2016/09/24 =
* Tweak - Update text domain for full support of translation with new name for translate file is 'woocommerce-email-inquiry-cart-options.po'
* Fix - Apply 'html_entity_decode' for email subject
* Tweak - Tested for full compatibility with WordPress version 4.6.1
* Tweak - Tested for full compatibility with PHP 7.0
* Credit - Thanks to mpek for raising the translation issue on wordpress.org support forum
* Credit - Thanks to WooCommerce Quotes and Orders customer John Phipps for reporting the email subject line special characters encoded bug

= 1.4.1 - 2016/08/20 =
* Tweak - Tested for Full compatibility with WordPress 4.6.0
* Tweak - Tested for full compatibility with WooCommerce version 2.6.4
* Fix - Compatibility with WooCommerce Subscriptions plugin. Email Inquiry button display on subscription and variable subscription products

= 1.4.0 - 2016/07/15 =
* Feature - Plugin framework Mobile First focus upgrade
* Feature - Massive improvement in admin UI and UX in PC, tablet and mobile browsers
* Feature - Introducing opening and closing Setting Boxes on admin panels.
* Feature - Added Plugin Framework Customization settings. Control how the admin panel settings show when editing.
* Feature - Moved Plugin admin settings from WordPress admin menu sidebar to WooCommerce sub menu item - Email and Cart
* Feature - Plugin admin panel now has just 2 tabs, Rules and Roles, Email Inquiry
* Feature - Removed all upgrade version Email Inquiry & Cart Premium, Email Inquiry Ultimate and Quotes & Orders settings from admin panels
* Feature - Email Inquiry Tab. Combined 5 tabs and 5 sub menus into 1 tab and 2 sub menus
* Feature - Includes a script to automatically combine sub category tables into the Tabs main table when upgrading
* Feature - Added Option to set Google Fonts API key to directly access latest fonts and font updates from Google
* Feature - Added Default Form auto Reply sender (customer) for Email Inquires received by admin
* Feature - Added full support for Right to Left RTL layout on plugins admin dashboard.
* Feature - Added a 260px wide images to the right sidebar for support forum link, Documentation links.
* Feature - Added 'Line Height' option into Typography control of plugin framework
* Tweak - Major overhaul of the admin panel Description and Help text
* Tweak - Update select type of plugin framework for support group options
* Tweak - Update plugin framework style for support 'Line Height' option of Typography control
* Tweak - Update Typography Preview script for apply 'Line Height' value to Preview box
* Tweak - Update the generate_font_css() function with new 'Line Height' option
* Tweak - Replace all hard code for line-height inside custom style of email template by new dynamic 'Line Height' value
* Tweak - Tested for full compatibility with WooCommerce version 2.6.2
* Tweak - Tested for full compatibility with WordPress version 4.5.3

= 1.3.4 - 2016/06/18 =
* Tweak - Tested for full compatibility with WooCommerce major version 2.6.0
* Tweak - Tested for full compatibility with WooCommerce version 2.6.1

= 1.3.3 - 2016/04/05 =
* Tweak - Define new 'strip_methods' argument for Uploader type, allow strip http/https or no
* Tweak - Saved the time number into database for one time customize style and Save change on the Plugin Settings
* Tweak - Replace version number by time number for dynamic style file are generated by Sass to solve the issue get cache file on CDN server
* Tweak - Register fontawesome in plugin framework with style name is 'font-awesome-styles'
* Tweak - Update plugin framework to latest version
* Tweak - Tested for full compatibility with WordPress major version 4.5
* Tweak - Tested for full compatibility with WooCommerce version 2.5.5
* Fix - call session_start() before html is printed on screen for fix PHP warning

= 1.3.2 - 2016/01/21 =
* Tweak - Tested for full compatibility with WooCommerce version 2.5.0
* Tweak - Tested for full compatibility with WordPress version 4.4.1
* Tweak - Define new 'Background Color' type on plugin framework with ON | OFF switch to disable background or enable it
* Tweak - Define new function - hextorgb() - for convert hex color to rgb color on plugin framework
* Tweak - Define new function - generate_background_color_css() - for export background style code on plugin framework that is used to make custom style
* Tweak - Update core style and script of plugin framework for support Background Color type
* Tweak - Update plugin framework to latest version
* Tweak - Updated required WordPress version to 4.1 for full compatibility with WooCommerce plugin
* Tweak - Change 'priority' to 20 for called Email Inquiry script at footer so that it need to run after jQuery is loaded

= 1.3.1 - 2015/12/17 =
* Feature - Added full support for Right to Left RTL layout on plugins admin dashboard
* Tweak - Tested for full compatibility with WordPress major version 4.4
* Tweak - Tested for full compatibility with WooCommerce version 2.4.12
* Tweak - Change old Uploader to New UI of Uploader with Backbone and Underscore from WordPress
* Tweak - Update the uploader script to save the Attachment ID and work with New Uploader
* Tweak - Change call action from 'wp_head' to 'wp_enqueue_scripts' and use 'wp_enqueue_style' function to load dynamic style for better compatibity with minify feature of caching plugins
* Tweak - Change call action from  'wp_head' to 'wp_enqueue_scripts' to load  google fonts
* Tweak - Updated a3 Plugin Framework to the latest version

= 1.3.0 - 2015/09/01 =
* Tweak - Tested for full compatibility with WooCommerce Version 2.4.6
* Tweak - Added Settings text link to plugins menu on WordPress Plugins page for faster access to plugins dashboard.
* Fix - Added 'box-sizing: initial;' for #fancybox-wrap ID to the Close button show correct on top right corner of Fancybox pop-up

= 1.2.9 - 2015/08/20 =
* Tweak - include new CSSMin lib from https://github.com/tubalmartin/YUI-CSS-compressor-PHP-port into plugin framework instead of old CSSMin lib from http://code.google.com/p/cssmin/ , to avoid conflict with plugins or themes that have CSSMin lib
* Tweak - make __construct() function for 'Compile_Less_Sass' class instead of using a method with the same name as the class for compatibility on WP 4.3 and is deprecated on PHP4
* Tweak - change class name from 'lessc' to 'a3_lessc' so that it does not conflict with plugins or themes that have another Lessc lib
* Tweak - Tested for full compatibility with WordPress major version 4.3.0
* Tweak - Tested for full compatibility with WooCommerce Version 2.4.4
* Fix - Check 'request_filesystem_credentials' function, if it does not exists then require the core php lib file from WP where it is defined

= 1.2.8 - 2015/06/04 =
* Tweak - Tested for full compatibility with WooCommerce Version 2.3.10
* Tweak - Tested for full compatibility with WordPress Version 4.2.2
* Tweak - Security Hardening. Removed all php file_put_contents functions in the plugin framework and replace with the WP_Filesystem API
* Tweak - Security Hardening. Removed all php file_get_contents functions in the plugin framework and replace with the WP_Filesystem API
* Fix - Update dynamic stylesheet url in uploads folder to the format <code>//domain.com/</code> so it's always is correct when loaded as http or https

= 1.2.7 - 2015/05/05 =
* Tweak - Tested for full compatibility with WordPress Version 4.2.1
* Fix - Removed check_ajax_referer() call on frontend for compatibility with PHP caching plugins. Was returning -1 to js success call-back.

= 1.2.6 - 2015/04/23 =
* Fix - Move the output of <code>add_query_arg()</code> into <code>esc_url()</code> function to fix the XSS vulnerability identified in WordPress 4.1.2 security upgrade

= 1.2.5 - 2015/04/21 =
* Tweak - Tested and Tweaked for full compatibility with WordPress Version 4.2.0
* Tweak - Tested and Tweaked for full compatibility with WooCommerce Version 2.3.8
* Tweak - enqueue the 'a3rev-admin-flat-ui-style' script on product edit page to fix the height of chosen multiple drop down on meta box
* Tweak - Update style of plugin framework. Removed the [data-icon] selector to prevent conflict with other plugins that have font awesome icons

= 1.2.4 - 2015/03/19 =
* Tweak - Tested and Tweaked for full compatibility with WooCommerce Version 2.3.7
* Tweak - Tested and Tweaked for full compatibility with WordPress Version 4.1.1

= 1.2.3 - 2015/02/13 =
* Tweak - Major upgrade for full compatibility with WooCommerce major version release 2.3.0 with backward compatibility to WC 2.2.0
* Tweak - Tested fully compatible with WooCommerce just released version 2.3.3
* Tweak - Changed WP_CONTENT_DIR to WP_PLUGIN_DIR. When an admin sets a custom WordPress file structure then it can get the correct path of plugin

= 1.2.2 - 2015/02/02 =
* Tweak - Removed CSS Class input box from the Default Email form button style settings.
* Tweak - Tested for 100% compatibility with WooCommerce version 2.2.11
* Tweak - Tested and Tweaked for 100% compatibility with WordPress version 4.1.0
* Tweak - Added Link to new plugins a3 Lazy Load and a3 Portfolio to the Free WordPress plugins list in yelow sidebar.
* Fix - Sass compile path not saving on windows xampp.

= 1.2.1 - 2014/09/12 =
* Tweak - Tested 100% compatible with WooCommerce 2.2.2
* Tweak - Tested 100% compatible with WordPress Version 4.0
* Tweak - Added WordPress plugin icon
* Fix - Changed __DIR__ to dirname( __FILE__ ) for Sass script so that on some server __DIR___ is not defined

= 1.2.0 - 2014/09/03 =
* Feature - Converted all front end CSS #dynamic {stylesheets} to Sass #dynamic {stylesheets} for faster loading.
* Feature - Convert all back end CSS to Sass.
* Tweak - Updated google font face in plugin framework.
* Tweak - Tested 100% compatible with WooCommerce Version 2.2 and backwards to v2.1

= 1.1.0.4 - 2014/06/28 =
* Tweak - Change wp_register_script( 'a3rev-chosen') to wp_register_script( 'a3rev-chosen-new')
* Tweak - Added all Quotes and Orders settings to admin dashboard for full upgrade compatibility
* Tweak - Added Italian Translation thanks to Fabio Biocchetti
* Fix - Add @ for called session_start() function to fix uncaught header warning message.

= 1.1.0.3 - 2014/06/17 =
* Tweak - Updated chosen js script to latest version 1.0.1 on the a3rev Plugin Framework
* Tweak - Added support for placeholder feature for input, email , password , text area types
* Tweak - Tested 100% compatible with WooCommerce version 2.1.11

= 1.1.0.2 - 2014/05/26 =
* Feature - Show uploaded files as Hyplerlinked File name on Order Received page and customer email. WooCommerce by default shows URL.
* Tweak - Changed add_filter( 'gettext', array( $this, 'change_button_text' ), null, 2 ); to add_filter( 'gettext', array( $this, 'change_button_text' ), null, 3 );
* Tweak - Update change_button_text() function from ( $original == 'Insert into Post' ) to ( is_admin() && $original === 'Insert into Post' )
* Tweak - Tested 100% compatible with WooCommerce Version 2.1.9
* Tweak - Tested 100% compatible with WordPress Version 3.9.1

= 1.1.0.1 - 2014/04/28 =
* Tweak - Checked and updated for full compatibility with WooCommerce Version 2.1.7 and WordPress version 3.9
* Tweak - Updated Framework help text font for consistency.
* Tweak - Added remove_all_filters('mce_external_plugins'); before call to wp_editor to remove extension scripts from other plugins.

= 1.1.0 - 2014/01/25 =
* Feature - Upgraded for 100% compatibility with WooCommerce Version 2.1 with backward compatibility to Version 2.0
* Feature - Added all required code so plugin can work with WooCommerce Version 2.1 refactored code.
* Tweak - Added Custom encode to prevent email clients automatically adding <a> tag to URL's in form message.
* Tweak - Edited Grid View text on admin panel to Product Card for consistency.
* Tweak - Added description text to the top of each Pro Version yellow border section
* Tweak - Tested for compatibility with WordPress version 3.8.1
* Fix - Email Inquiry sending duplicate emails on themes that have script that duplicate the click event

= 1.0.9.6 - 2013/12/24 =
* Tweak - a3rev Plugin Framework upgrade - all switch text show UPPERCASE
* Tweak - Updated plugins wp-admin menu item vector image.

= 1.0.9.5 - 2013/12/17 =
* Fix - Plugins wp-admin menu icon display in all versions prior to WordPress 3.8.0.

= 1.0.9.4 - 2013/12/16 =
* Feature - a3rev Plugin Framework admin interface upgraded to 100% Compatibility with WordPress v3.8.0 with backward compatibility.
* Feature - a3rev framework 100% mobile and tablet responsive, portrait and landscape viewing.
* Tweak - Upgraded dashboard switch and slider to Vector based display that shows when WordPress version 3.8.0 is activated.
* Tweak - Upgraded all plugin .jpg icons and images to Vector based display for full compatibility with new WordPress version.
* Tweak - Yellow sidebar on Pro Versions Menus dose not show in Mobile screens to optimize screen space.
* Tweak - Tested 100% compatible with WP 3.8.0
* Fix - Upgraded array_textareas type for Padding, Margin settings on the a3rev plugin framework

= 1.0.9.3 - 2013/11/20 =
* Fix - add filter to 'single_add_to_cart_text' for hide Add to Cart button for Child Products in Grouped Product when Hide Add to Cart Rule is ON.
* Fix - add action to 'woocommerce_before_template_part' and 'woocommerce_after_template_part' for hide Child Products Quantity selector in Grouped Product when Hide Add to Cart is ON.
* Credit - Thanks to Marc Schwinges Underdog Productions South Africa for alerting us to the issue and wp-admin and ftp access to find and fix the bug.

= 1.0.9.2 - 2013/11/18 =
* Tweak - Moved - Hide Add to Cart and Hide Price Rules and Roles to the top of the Rules and Roles menu.
* Tweak - Moved the Email Inquiry Rules & Roles settings from Rules & Roles menu to Email Inquiry menu > Settings tab.
* Tweak - Moved the show Email Inquiry feature on Product Cards settings from Button Style tab to settings tab.
* Tweak - Changed Product Cards activation syntax - ON is enables, OFF is disabled.
* Tweak - Product Page Email & Cart Meta UI design upgrade. New tabs layout - Cart & Price | Email Inquiry | Read More - for ease of navigation.
* Tweak - Added new main Menu Item - Read More with Tabs - Settings | Button Style (Active for Ultimate Inquiry Ultimate and Quotes & Orders Versions)
* Fix - Google fonts preview changes conflict.

= 1.0.9.1 - 2013/11/06 =
* Tweak - Stricter sanitization of Default Form Message input field. Only allow input of plain text with auto paragraph on line break.
* Tweak - Added function .replace(/^\s+|\s+$/g, '') to check form for empty spaces for required fields Name, Email and Phone.
* Tweak - Default Form Success Message Pop-up auto resizes to whatever the tall of the success message content is.
* Tweak - Added class .email_inquiry_cb for Colorbox Pop-up tool content custom background display.

= 1.0.9 - 2013/11/01 =
* Tweak - Removed dynamic pop-up wide setting and replaced with static pop-up max wide.
* Tweak - Pop-up tools wide under 520px shows 100% wide of the screen for mobiles in portrait or landscape.
* Tweak - Default Form breaks down for greatly enhanced display in tablets and mobiles.
* Tweak - Default Form - added static 20px content padding that auto reduces to 5px in tablets and mobiles.
* Tweak - Default From - vertical alignment of the text fields
* Tweak - Default Form - changed the default form fonts on install from Bold to Normal.
* Tweak - Default Form Success Message uses form custom background colour.
* Tweak - Button Style - changed default button padding on install from 0px to 5px
* Tweak - Button Style - added blue box help text and fixed a small typo.
* Tweak - Rules & Roles - added blue box help text for Product Page Rule 'Show Email Inquiry'
* Fix - Default form success message showing HTML tags with text.

= 1.0.8 - 2013/10/25 =
* Feature - Major plugin upgrade. Full code rework.
* Feature - Upgraded the plugin to the newly developed a3rev admin Framework with app style interface.
* Feature - Moved admin from WooCommerce settings tab onto its own Email Inquiry & Cart Options main menu item with sidebar sub menu.
* Feature - Email Inquiry & Cart Options sub menus, Rules & Roles | Email Inquiry | Quotes Mode | Orders Mode
* Feature - Email Inquiry menu broken up into tabs - Settings | Default Form | Custom Form | Button Style | Pop-Up Style
* Feature - New admin UI features check boxes replaced by switches, some dropdowns replaced by sliders.
* Feature - Added intuitive triggers for admin panel settings. When selected corresponding feature settings appear.
* Feature - Added choice of 350 Google fonts to the existing 17 websafe fonts in all new single row font editor.
* Feature - New on page instant previews for Font editor.
* Feature - Rules & Roles - Activate any Rule for logged in user Role by adding the Role to the Rule.
* Feature - Rules and Roles - incorporate help message under each Rules Roles. Show when the Rule is turned on.
* Feature - Settings - Added House Keeping function to settings. Clean up on Deletion. Option - Choose if you ever delete this plugin it will completely remove all tables and data it has created.
* Tweak - Fixed up all existing typos on admin panel.
* Tweak - Updated support url to WordPress support forum.
* Tweak - Updated translation submission URL
* Tweak - Updated Lite Version support text on plugins description.
* Fix - Plugins admin script and style not loading in Firefox with SSL on admin. Stripped http// and https// protocols so browser will use the protocol that the page was loaded with.

= 1.0.7 - 2013/08/09 =
* Feature - Default Contact Form new options for 'Email Pop-up Font Styling'. Use WYSIWYG settings to set the default pop-ups Font type (choose from 17 web safe fonts), size, style and colour.
* Tweak - Tested for full compatibility with WordPress v3.6.0
* Fix - Script validate email for default contact form. Old script conflicted with WordPress 3.6.0 jQuery 1.10.2. Conflict caused the popup tools to break.
* Fix - Added box-sizing:content-box class attribute for compatibility with new WordPress Twenty Thirteen default theme.

= 1.0.6 - 2013/06/28 =
* Fix - Replaced hardcode iso-8859-1 charset to dynamic get_option('blog_charset')

= 1.0.5 - 2013/06/22 =
* Feature - Email Inquiry - Settings. Added option to set padding in px above and below the Email Inquiry button / Hyperlink.

= 1.0.4 - 2013/06/21 =
* Feature - Email Inquiry - Settings. Added option to show Email Inquiry by Hyperlinked text instead of button.
* Feature - Email Inquiry - Settings. Added option to set relative Button or link position, Above or Below add to cart button position.
* Feature - Email Inquiry - Settings. Added option to set padding for button / link position.
* Feature - Email Inquiry - Settings. Added option to show Email Inquiry button / Link on product grid view extracts on shop and archives pages.
* Tweak - Upgraded admin Yellow sidebar box information to show the 3 available feature Upgrade plugins.

= 1.0.3.1 - 2013/06/05 =
* Tweak - Upgraded and synched the plugins code to be inline with the new WooCommerce Quotes and Orders plugin. This allows users to seamlessly upgrade to that plugin at any time.
* Tweak - Updated the plugins support links to the new a3rev support forum.

= 1.0.3 - 2013/05/04 =
* Tweak - Moved plugin admin panel from a single tab on WooCommerce Settings to its own link â€˜Email & Cart Options' on the WooCommerce wp-admin menu.
* Tweak - Added main tab for Rules & Roles settings.
* Tweak - Added Email Inquiry main tab with related sub tabs.
* Tweak - Added when install and activate plugin link redirects to the plugins dashboard instead of the wp-plugins dashboard.
* Tweak - Updated plugins Wiki documentation.
* Fix - Updated all JavaScript functions so that the plugin is compatible with jQuery Version1.9 and backwards to version 1.6. WordPress still uses jQuery version 1.8.3. In themes that use Google js Library instead of the WordPress jQuery then there was trouble because Google uses the latest jQuery version 1.9. There are a number of functions in jQuery Version 1.9 that have been depreciated and hence this was causing errors with the jQuery function in the plugin.
* Fix - Did a full WP_DEBUG. All uncaught exceptions, notices, warnings and errors fixed.

= 1.0.2 - 2013/04/10 =
* Fix - WooCommerce Reviews form opening in duplicate popup tools, PrettyPhoto and Fancybox caused by our old WooCommerce v1.6 fancybox lib.
* Fix - Bug for users who have https: (SSL) on their sites wp-admin but have http on sites front end. This was causing a -1 to show when email pop-up form is called. wp-admin with SSL applied only allows https: but the url of admin-ajax.php is http: and it is denied hence returning the ajax -1 error. Fixed by writing a filter to recognize when https is configured on wp-admin and parsing correctly.

= 1.0.1 - 2013/03/14 =
* Fix - Can't activate the plugin on some sites . The problem was in php configuration differences .It was caused by php configuration related to short <?php syntax which allows to use <? instead.

= 1.0.0 - 2013/03/07 =
* First working release


== Upgrade Notice ==

= 3.4.1 =
This release has various tweaks for compatibility with WordPress 6.6 and WooCommerce 8.9.3

= 3.4.0 =
This feature release adds auto fill name and email on default form for logged in users.

= 3.3.2 =
This maintenance release has plugin framework updates for compatibility with PHP 8.1 onwards, plus backward compatibility to WooCommerce 6.0.

= 3.3.1 =
This maintenance release has a Code Tweak for compatibility with WordPress 6.4 and WooCommerce 8.2

= 3.3.0 =
This feature release adds a "Product Inquiry Button" Block for use in Gutenberg Templates. Also compatibility with WooCommerce 8.0.3 and WordPress 6.3

= 3.2.2 =
This maintenance release has 2 bug fixes for compatibility with WooCommerce 7.9 and WordPress 6.2.2 or higher.

= 3.2.1 =
This maintenance release fixes a small PHP bug that emerged from the 3.2.0 release.

= 3.2.0 =
* This feature release adds insert Email Inquiry by 2 new shortcodes. Works with New WC Single Product Page Bock Template and page builders like Elementor.

= 3.1.0 =
This release has compatibility with WordPress 6.2.0, WooCommerce 7.6.0 plus declared compatibility with WooCommerce HPOS.

= 3.0.0 =
This feature release removes the fontawesome lib and replaces icons with SVGs plus adds Default Topography option to font controls and has compatibility with WooCommerce 7.2

= 2.9.0 =
This feature release adds Default font from the theme to the font control.

= 2.8.2 =
This maintenance release has 1 bug fix and compatibility with WooCommerce 7.1

= 2.8.1 =
This maintenance release has a security vulnerability patch, plus compatibility with WordPress major version 6.1.0 and WooCommerce version 7.0

= 2.8.0 =
This release is for compatibility with WordPress major version 6.0 and WooCommerce version 6.5.1. It and includes various code tweaks and tweaks to harden security.

= 2.7.0 =
This release has a new Google Fonts API Validation feature plus compatibility with WordPress 5.9 and WooCommerce 6.1.1

= 2.6.3 =
This maintenance release has fixes for compatibility with PHP version 8.x

= 2.6.2 =
This maintenance release has a compatibility bug fix for WooCommerce version 5.9.0 compatibility

= 2.6.1 =
This maintenance release has a PHP fatal Error fix that has arisen out of yesterdays version 2.6.0 feature release.

= 2.6.0 =
This feature release adds compatibility with the WooCommerce Product Bundles plugin

= 2.5.1 =
This maintenance release completes full compatibility with the WooCommerce Products Add-on plugin.

= 2.5.0 =
This feature release adds full compatibility with WooCommerce Product Add-ons.

= 2.4.11 =
This maintenance release has code tweaks for compatibility with WordPress Major version 5.8, WooCommerce version 5.5.1 and some Security Hardening.

= 2.4.9 =
This maintenance release updates 23 deprecated jQuery functions for compatibility with the latest version of jQuery in WordPress 5.7

= 2.4.8 =
This maintenance release is for compatibility with WordPress 5.7 and WooCommerce 5.1

= 2.4.7 =
This maintenance release is for compatibility with WooCommerce major version 4.9.0

= 2.4.6 =
This is an important maintenance release that updates our scripts for compatibility with the latest version of jQuery released in WordPress 5.6

= 2.4.5 =
* This maintenance release is for compatibility with WooCommerce 4.8.0

= 2.4.4 =
This maintenance release has tweaks and a fix for compatibility with WordPress major version 5.6, WooCommerce 4.7.1 and PHP 7.4.8

= 2.4.3 =
This maintenance release is for compatibility with WordPress major version 5.5 and WooCommerce 4.3.1.

= 2.4.2 =
This maintenance release removes form modal popup h tags plus has compatibility with WooCommerce 4.1.0

= 2.4.1 =
This maintenance release is for compatibility with WordPress 5.4, WooCommerce 4.0.1, Travis CI build unit test for compliance with WordPress PHP coding standards and PHP tweaks for compatibility with PHP v 7.0 to 7.4

= 2.4.0 =
This feature release completes the full refactor (frontend and backend) of the plugins PHP to Composer plus compatibility with WordPress 5.3.2 and WooCommerce 3.8.1

= 2.3.0 =
This feature release has a lot including compatibility with WooCommerce 3.8.0, WordPress 5.3 whilst maintaining backward compatibility, PHP upgrade to Composer PHP Dependency Manger and a full security review and update

= 2.2.5 =
Maintenance upgrade to add support for Hide Add to Cart and show Read More on product cards added by WooCommerce Gutenberg block.

= 2.2.4 =
This is a maintenance upgrade to fix a potentially fatal error conflict with sites running PHP 7.3 plus compatibility with WordPress v 5.2.2 and WooCommerce 3.6.4

= 2.2.3 =
This maintenance update has tweaks for compatibility with WordPress 5.2.0 and WooCommerce 3.6.0 major new versions whilst maintaining backward compatibility

= 2.2.2 =
This maintenance upgrade fixes an issue with Variation Price and description display when add to cart is hidden plus compatibility with WooCommerce 3.5.7 and upcoming WordPress 5.2

= 2.2.1 =
This maintenance update is for compatibility with WordPress 5.0.2, WooCommerce 3.5.3 and PHP 7.3. It also includes performance updates to the plugin framework.

= 2.2.0 =
This feature upgrade gives options between show email inquiry on frontend as a Button or Hyperlink text with full style options plus compatibility with WordPress 4.9.7

= 2.1.0 =
This Feature Upgrade adds a new Product Page Rule, Hide Product Price plus full compatibility with WooCommerce Quotes and Orders major version 3.0.0, WooCommerce On Page Checkout and WooCommerce 3.4.3

= 2.0.1 =
Maintenance update fixes a bug with email inquiry showing under footer on some sites plus a tweak to the modal pop up in mobile and fix on framework setting options.

= 2.0.0 =
Major Upgrade. V2 is a massive step forward in the plugins development with 11 new features, new pop up tool, introduction of templating and multiple coding standard enhancements

= 1.4.8 =
Maintenance Update. Compatibility with WordPress 4.9.6 and WooCommerce 3.4.0 and the new GDPR compliance requirements for users in the EU

= 1.4.7 =
Maintenance Update. This version updates the Plugin Framework to v 2.0.2, adds full compatibility with a3rev Dashboard, WordPress v 4.9.4 and WooCoomerce v 3.3.1

= 1.4.6 =
Maintenance Upgrade. Tweaks for compatibility with WooCommerce 3.2.0 and WordPress 4.8.2

= 1.4.5 =
Maintenance Update. 2 code tweaks for compatibility with WordPress major version 4.8.0 and WooCommerce version 3.0.7

= 1.4.4 =
Major Maintenance Update. 5 Code tweaks for full compatibility with WooCommerce v 3.0.2 with backward compatibility to WC v 2.6.0 plus compatibility with WordPress v 4.7.3

= 1.4.3 =
Maintenance Update. 4 code tweaks and full compatibility with WooCommerce version 2.6.6

= 1.4.2 =
Maintenance Update. 1 email subject text bug fix plus a tweak add text domain for translations and full compatibility with WordPress v 4.6.1 and PHP 7.0

= 1.4.1 =
Maintenance Update. 1 bug fix when used with WooCommerce Subscription plugin. Full compatibility with WordPress version 4.6.0 and WooCommerce Version 2.6.4

= 1.4.0 =
Major Feature Upgrade. 14 new features plus 6 code tweaks. Find new admin menu under the WooCommerce menu. New Admin UI, Font Line Height, Auto reply sender, Google Fonts API and much more

= 1.3.4 =
Maintenance Update. Tweaks for full compatibility with WooCommerce version 2.6.1

= 1.3.3 =
Maintenance Update. 5 Tweaks and 1 bug fix for full compatibility with upcoming major WordPress version 4.5.0 and WooCommerce Version 2.5.5

= 1.3.2 =
Major Upgrade for full compatibility with WooCommerce v2.5 with backward compatibility to v2.1 - 7 major code Tweaks

= 1.3.1 =
Feature Upgrade. 1 new feature plus 5 code tweaks for full compatibity with WordPress 4.4 and WooCommerce 2.4.12

= 1.3.0 =
Maintenance Upgrade. 2 Tweak and 1 bug fixes for full compatibility with WooCommerce Version 2.4.6

= 1.2.9 =
Major Maintenance Upgrade. 5 Code Tweaks plus 1 bug fixes for full compatibility with WordPress v 4.3.0 and WooCommerce v 2.4.4

= 1.2.8 =
Important Maintenance Upgrade. 2 x major a3rev Plugin Framework Security Hardening Tweaks plus 1 https bug fix and full compatibility with WooCommerce 2.3.10 and WordPress 4.2.2

= 1.2.7 =
Maintenance Update. 1 Bug fix for full compatibility with PHP caching plugins and full compatibility with WordPress version 4.2.1

= 1.2.6 =
Important Security Patch! - please run this update now. Fixes XSS vulnerability declared and patched in WordPress Security update v 4.1.2

= 1.2.5 =
Maintenance upgrade. Code tweaks for full compatibility with WordPress 4.2.0 and WooCommerce 2.3.8

= 1.2.4 =
Upgrade now for full compatibility with WooCommerce Version 2.3.7 and WordPress version 4.1.1

= 1.2.3 =
Upgrade now for full compatibility with WooCommerce major version release 2.3.0 with backward compatibility to WooCommerce v 2.2.0

= 1.2.2 =
Upgrade now for full compatibility with WooCommerce 2.2.11 and WordPress 4.1. Includes 1 code tweak and a bug fix.

= 1.2.1 =
Upgrade now for 1 Sass bug fix and full compatibility with WooCommerce Version 2.2.2 and WordPress 4.0

= 1.2.0 =
Major version upgrade. Full front end and back end conversion to Sass and Tweaks for full compatibility with WooCommerce 2.2

= 1.1.0.4 =
Upgrade your plugin now for 1 framework code tweak, 1 bug fix and new Italian translation.

= 1.1.0.3 =
Upgrade now for 2 framework code tweaks that makes your plugin fully compatible with WooCommerce version 2.1.11

= 1.1.0.2 =
Update now for 1 new feature, 2 a3rev Plugin framework Tweaks and full compatibility with WooCommerce Version 2.1.9 and WordPress 3.9.1

= 1.1.0.1 =
Upgrade now for full compatibility with WooCommerce Version 2.1.7 and WordPress version 3.9 plus 2 framework tweaks.

= 1.1.0 =
Upgrade now for full compatibility with soon to be released WooCommerce Version 2.1 and just released WordPress version 3.8.1. Includes full backward compatibly with versions 2.0 to 2.0.20 plus 1 bug fix.

= 1.0.9.6 =
Update to latest version of the a3rev plugin Framework. Relatively minor admin panel cosmetic tweaks. Low priority.

= 1.0.9.5 =
Upgrade now to fix the plugins wp-admin display icon in all WordPress version prior to 3.8.0

= 1.0.9.4 =
Upgrade your plugin now for a3rev Plugin Framework compatibility with the new WordPress version 3.8.0 admin UI upgrade. Admin panel full mobile and tablet responsive display.

= 1.0.9.3 =
Update your plugin now for 2 Bug fixes. Hide Grouped products Quantity selectors when hide add to cart rule is ON.

= 1.0.9.2 =
Upgrade now for 4 admin panel UI tweaks plus Product Page Meta UI redesign.

= 1.0.9.1 =
Upgrade now for stricter default form text input field sanitization, improved default form success message pop-up display and Colorbox Pop-up content display tweak.

= 1.0.9 =
Major scheduled upgrade to the Default Contact Form, including 7 new features, and 1 bug fix.

= 1.0.8 =
Major plugin upgrade! All new intuitive app style admin interface featuring conditional logic and associated features and 1 known bug fix.

= 1.0.7 =
Update now for 100% compatibility with WordPress v3.6.0. Includes 2 bug fixes and 1 new Default Contact Form features - pop-up form text editor.

= 1.0.6 =
Update your plugin now for an important charset bug fix.

= 1.0.4 =
Upgrade now to add functionality from 4 new features.

= 1.0.3 =
Upgrade now for major admin User interface upgrade and various minor bug fixes.

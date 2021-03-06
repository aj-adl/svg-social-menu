=== SVG Social Menu ===
Contributors: FlorianBrinkmann
Tags: widget, social, menu, svg, vector, custom nav menu
Requires at least: 3.0.1
Tested up to: 4.4.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display your social media profile links with vector icons using a custom navigation menu.

== Description ==

This plugin adds a Widget that allows you to show show the social media links as vector icons.

To use it, follow these steps after activation:

1. Create a menu with links to your social media channels
2. Select “SVG Social Menu” as menu location and save it
3. Drag the widget “SVG Social Menu” in one of your widget areas

You can filter the custom CSS with the following code in your theme, where `$styles` is the CSS:

`function slug_edit_svg_social_menu_styles( $styles ) {
    $styles = '';
}

add_filter( 'svg_social_menu_inline_style', 'slug_edit_svg_social_menu_styles' );`

The following social network URLs are supported:

* plus.google.com
* wordpress.org
* wordpress.com
* facebook.com
* twitter.com
* dribbble.com
* pinterest.com
* github.com
* tumblr.com
* youtube.com
* flickr.com
* vimeo.com
* instagram.com
* linkedin.com
* xing.de
* xing.com
* /feed

If you want more or have other problems, you can create an issue on [GitHub](https://github.com/FlorianBrinkmann/svg-social-menu).

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/svg-social-menu` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the “Plugins” screen in WordPress
3. Create a menu with links to your social media channels
4. Select “SVG Social Menu” as menu location and save it
5. Drag the widget “SVG Social Menu” in one of your widget areas

== Changelog ==

= 1.0 =
* initial release
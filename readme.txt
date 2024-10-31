=== No Follow All External Links ===

Contributors: gearpressstudio
Tags: NoFollow, No Follow, Outbound Links, SEO, Crawler, External Links
Requires at least: 3.5
Tested up to: 4.9.1
Stable tag: 2.3.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

No Follow All External Links is a simple, lightweight plugin which automatically adds rel=”nofollow” to all external links. You can easily declare a “follow” class for individual links as required.

This plugin also gives you the option to open all external links in a new window, by adding target=“_blank”. You can easily declare a “samewindow” class for individual links as required.

This makes it the ideal plugin for websites which have a large number of outbound links within existing posts, pages and content - where it would be too time consuming to add them all individually.

You can choose to target all links regardless of whether they are placed in the theme, content, widgets, etc. Alternatively you can target links within the Page/Post Content only.

This is not visible in the page or post editor because it does not take effect until the page actually renders.

The plugin now allows you to remove rel="noopener noreferrer" as requested by our users. Although this is a security feature added by Wordpress, it may stop many affiliate links from working. We have added the sitewide option to add / remove this feature.

= Features =

* Easily add rel=“nofollow” for all external links
* Easily add target=“_blank” for all external links
* The plugin will NOT nofollow internal links, or open them in a new window
* ALL content types supported - Pages, Posts, Widgets, etc
* Easily mark individual links with “follow” or “samewindow” classes, to exclude them from being nofollowed or opened in a new window
* Exceptions can be added to exclude entire domains or individual URLs in the settings menu
* Prevent Wordpress from adding rel="noreferrer noopener" to new target="_blank" links
* New Feature: Easily remove rel="noopener noreferrer" from all external links with target="_blank"

== Frequently Asked Questions ==

= How do I nofollow links? =
Just install and activate the plugin - it’s a simple as that!

= If I deactivate the plugin, what will happen? =
The plugin doesn’t make any changes to your database so all links will revert to the original state (follow, same window by default)

= Do I have to nofollow all links individually? =
No, simply install and activate the plugin and it will automatically nofollow all external links, regardless of how many you have throughout your website.

== Installation ==

1. Upload folder to '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

= 2.3.0 =
* Refactored / Updated code base.
* Fixed several bugs.

= 2.2.0 =
* Added the ability to remove rel="noopener noreferrer" from all external links.

= 2.1.1 =
* Added missing javascript file for Admin Panel.

= 2.1.0 =
* Added the ability to open all external links in a new window.
* Added the ability to whitelist external domains/urls.
* Added the ability to target specific search bots.
* Added the ability to target all content or just post/page content.

= 2.0.0 =
* Rewritten plugin.

= 1.5 =
* Added the "follow" CSS class reader to enable or disable specific links.

= 1.0 =
* Initial Release.

=== Hide My Unused Pages ===
Contributors: sciencefreaks
Tags: wordpress, multisite, wpmu, blogs, sites, activity, inactive, hide
Requires at least: 3.2
Tested up to: 3.6
Stable tag: trunk

== Description ==
The widget Hide My Unused Pages changes thevisibility of a blog after it has had no activity for a specified amount of time. It is only for WordPress Multisite. This is meant for people running networks of blogs and hide the inactive sites.

This plugin uses WP_Cron to update the sites. I've created a filter in the plugin to edit the query of sites that are returned. There are also hooks for adding additional custom options to each of the settings.  

== Installation ==

1. Copy the plugin files to <code>wp-content/plugins/</code>

2. Network Activate plugin from Network Plugins page

3. From Network Admin dashboard, go to Settings -> Hide My Unused Pages and adjust settings.

== Screenshots ==

1. The Network Admin dashboard screen. Each of the options can be added on to using the hooks in the plugin.

== Changelog ==

= 1.0 =
* Initial release
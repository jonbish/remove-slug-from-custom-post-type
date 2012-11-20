=== Plugin Name ===
Contributors: jocke_gbg, jonbishop
Tags: slug, remove, post type, custom post type, remove slug
Requires at least: 2.9
Tested up to: 3.3
Stable tag: trunk

Add rewrite rules for custom post type so that the urls for them are in the same way as normal posts: http://siteurl/%custom_post_type_title%/.

== Description ==

In WordPress 2.9 custom post type was introduced, that opened a new world for many WordPress developers. 
When it comes to removing the slug and not destroying the rewrite rules for other post types this plugin works great. 
This only concerns those who are using %postname% as permalink structure and want to add a custom post type so that 
the urls for them are in the same way as normal posts and pages: http://siteurl/%custom_post_type_title%/.

Find more useful tips and plugins: [Ultimate web tips](http://www.ultimatewebtips.com/ "More Wordpress plugins")

== Installation ==

1. Upload `remove-slug-custom-post-type` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Which permalink structure do I need to have for this to work? =

This only works if permalink structure is "/%postname%/

== Changelog ==

= 1.0.4 (jon) =
* Fixed error notice being displayed at wrong time
* Hard flush rewrite rules after post save

= 1.0.3 =
* Permalink regex fixed
* Suffix feature added

= 1.0.2 =
* Permalink bug fixed

= 1.0 =
* Released

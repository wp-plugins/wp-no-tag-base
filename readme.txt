=== WP No Tag Base ===
Contributors: Devin Walker
Donate link: http://www.wordimpressed.com/
Tags: tags, tag base, tag, permalinks, permastruct, links, seo, cms
Requires at least: 2.3
Tested up to: 3.0.1
Stable tag: trunk

This plugin will completely remove the mandatory 'Tag Base' from your tag permalinks (e.g. `/tag/my-tag/` to `/my-tag/`).

== Description ==

This plugin does the same as iDope's wp-no-category-base does except with tags.  WP-no-tag-base will completely remove the mandatory 'Tag Base' from your tag permalinks ( e.g. `wordimpressed.com/tag/my-tag/` to `wordimpressed.com/my-tag/` ).

The plugin requires no setup or modifying core wordpress files and will not break any links. It will also take care of redirecting your old tag links to the new ones.

<h3>Important Links:</h3>


[WP-No-Tag-Base Page](http://www.wordimpressed.com/plugins/wp-admin-icons-plugin "WP-Admin Icons Page")

[WordImpressed](http://www.wordimpressed.com/ "WordImpress - Developer's Site")

= Features =

1. Better and logical permalinks like `myblog.com/my-tag/` and `myblog.com/my-tag/my-post/`.
2. Simple plugin - barely adds any overhead.
3. Works out of the box - no setup needed.
4. No need to modify wordpress files.
5. Doesn't require other plugins to work.
6. Compatible with sitemap plugins.
8. Redirects old tag permalinks to the new ones (301 redirect, good for SEO).

== Installation ==

1. Upload `wp-no-tag-base.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. That's it! You should now be able to access your tags via http://myblog.com/my-tag/

Note: If you have Wordpress 2.7 or above you can simply go to 'Plugins' &gt; 'Add New' in the Wordpress admin and search for "WP No Tag Base" and install it from there.

== Frequently Asked Questions ==

= Why should I use this plugin? =

Use this plugin if you want to get rid of Wordpress' "Tag base" completely. The normal behaviour of Wordpress is to add '/tag' to your tag permalinks if you leave "Tag base" blank in the Permalink settings. So your tag links look like `myblog.com/tag/my-tag/`. With this plugin your tag links will look like `myblog.com/my-tag/` (or `myblog.com/my-tag/` in case of sub categories). 

Why do this?  Well, shorter URLs mean betting indexing and bottom line is: it's good for SEO.  Having the meaningless "tag" in your permalinks will dilute their keyword relevance.  Keep your tag permalinks tight with this plugin.


== Screenshots ==

1. WP-Admin Icons Logo
2. Wp-Admin Icons Default Screen
3. WP-Admin Icons Packaged Icon View


== Changelog ==

= 1.1 Updated plugin to refresh tag-base rewrite rules for newly created tags, deleted tags and edited tags.  Modified 1.0 Modified iDope's code to work for tags.  Could add both features and a GUI but have no time for now

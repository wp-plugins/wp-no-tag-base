=== WP No Tag Base ===
Contributors: Devin Walker; based from iDope's code
Donate link: http://wordimpressed.com/
Tags: tags, tag base, tag, permalinks, permastruct, links, seo, cms
Requires at least: 2.3
Tested up to: 3.0.1
Stable tag: trunk

This plugin will completely remove the mandatory 'Tag Base' from your tag permalinks (e.g. `/tag/my-tag/` to `/my-tag/`).

== Description ==

This plugin does the same as iDope's wp-no-category-base does except with tage.  WP-no-tag-base will completely remove the mandatory 'Tag Base' from your category permalinks ( e.g. `wordimpressed.com/tag/my-tag/` to `wordimpressed.com/my-tag/` ).

The plugin requires no setup or modifying core wordpress files and will not break any links. It will also take care of redirecting your old category links to the new ones.

= Features =

1. Better and logical permalinks like `myblog.com/my-tag/` and `myblog.com/my-tag/my-post/`.
2. Simple plugin - barely adds any overhead.
3. Works out of the box - no setup needed.
4. No need to modify wordpress files.
5. Doesn't require other plugins to work.
6. Compatible with sitemap plugins.
7. Works with multiple sub-categories.
8. Redirects old category permalinks to the new ones (301 redirect, good for SEO).

== Installation ==

1. Upload `wp-no-tag-base.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. That's it! You should now be able to access your categories via http://myblog.com/my-tag/

Note: If you have Wordpress 2.7 or above you can simply go to 'Plugins' &gt; 'Add New' in the Wordpress admin and search for "WP No Tag Base" and install it from there.

== Frequently Asked Questions ==

= Why should I use this plugin? =

Use this plugin if you want to get rid of Wordpress' "Category base" completely. The normal behaviour of Wordpress is to add '/category' to your category permalinks if you leave "Category base" blank in the Permalink settings. So your category links look like `myblog.com/category/my-category/`. With this plugin your category links will look like `myblog.com/my-category/` (or `myblog.com/my-category/sub-category/` in case of sub categories).


== Screenshots ==

1. Sorry nopes

== Changelog ==

= 1.0 Modified iDope's code to work for tags.  Could add both features and a GUI but have no time for now…

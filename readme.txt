=== Lorem Ipsum Generator Shortcode ===
Contributors: OpenWebStuff
Donate link: http://loremipsum-generator.com/
Tags: lorem ipsum, generator, filler text, dummy text, shortcode, plugin, posts, page, Post, admin, pages, wordpress
Requires at least: 2.8
Tested up to: 3.5.1
Stable tag: 1.0

Plugin that generates lorem ipsum dummy text in post and pages. 

== Description ==
Using this plugin you can generate lorem ipsum dummy text using shortcodes in your posts and pages.

This plugin is a wordpress version of http://loremipsum-generator.com/ tool.

= Usage = 
Add the `[lorem-ipsum]` shortcode to a post or page.

= Parameters =

All parameters are optional.

* start_with_lorem_ipsum - values: on/off, default: on
* paragraphs - number of paragraphs, values: 1-20, default: 1
* words - number of words, values: 1-1200, default: 69
* sentences - number of sentences, values: 1-20, default: 1
* randomize - randomize senteces, values: on/off, default: off

(words has a higher priority than sentences)

= Examples =

* [lorem-ipsum]
* [lorem-ipsum start_with_lorem_ipsum=off words=120 paragraphs=3 randomize=on]
* [lorem-ipsum words=100 sentences=2] - displays 100 words, not 2 sentences
* [lorem-ipsum sentences=2] - displays 2 sentences

== Installation ==

1. Extract archive and upload the 'lorem-ipsum-generator-shortcode' folder to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Navigate to 'Plugins' > 'Installed' in the WP admin dashboard. Locate `Lorem Ipsum Generator Shortcode` and click activate.
1. Now, you can use it in posts and pages. 


== Changelog ==

= 1.0 =
* First version.

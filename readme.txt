=== Tweeted From Twitter ===
Contributors: ShaneF, jdingman
Donate Link: http://bugssite.org/donate
Tags: twitter, tweet, tweets, post, page
Requires at least: 2.9.1
Tested up to: 2.9.1
Stable tag: 1.0.0

== Description ==

This plugin allows you to insert a Twitter post without having to copy and paste the status update from Twitter.

It automatically styles the twitter posts to one of the many default designs we offer. A theme can override the twitter post design as well by hooking into a filter. (Read Usage Section)

Props to [Jonathan Dingman] and [Dre Armeda] (http://wpvibe.com/) for the idea behind this plugin, testing and feedback. [Dre Armeda] did all of our twitter output designs.

== Installation ==

Requires PHP5 or greated to activate.

Use the WordPress plugin install or...

1. Extract the archive
2. Place 'tweeted' folder to the `/wp-content/plugins/` directory
3. Activate (Both Methods!)

And that is is!

== Screenshots ==

== Upgrade ==

=== Automatic ===
1. Use the plugin updater in WordPress or...

=== Manual ===
1. Delete the previous `include-tweets-from-twitter` folder from the `/wp-content/plugins/` directory
2. Upload the new `include-tweets-from-twitter` folder to the `/wp-content/plugins/` directory

== Usage ==

1. Place the Twitter Status URL inside [tweet] shortcode.

Note: URL has to be in this format from Twitter:

* http://twitter.com/[name]/status/[id number]
* http://twitter.com/[name]/statuses/[id number]

Filters
* twitter_tweet_override_output - 2 paramaters
** $tweet_output - the output that we do
** $content - the data array

== Change Log ==

= 1.0.0 (2010-01-16): =
* Initial Public Release

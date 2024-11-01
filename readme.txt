=== WP Tweets (Twitter plugin for WordPress) ===
Contributors: jaysonjc
Donate link: http://www.jaysonjc.com/projects#donations
Tags:twitter, tweets, widget, jQuery
Requires at least: 2.7
Tested up to: 3.0.1
Stable tag: 1.1

Displays public tweets from a twitter user.

== Description ==
WP Tweets enables you to be embed your twitter tweets. This plugin supports the following features,

* Configure twitter username and number of tweets displayed.
* Is very lightweight and uses client side fetch.
* Free online support for CSS customization - [Project Page - WP Tweets](http://www.jaysonjc.com/projects/wordpress-plugins/wp-tweets-twitter-plugin-for-wordpress).
* Widget ready.

Please see the [official project page](http://www.jaysonjc.com/projects/wordpress-plugins/wp-tweets-twitter-plugin-for-wordpress) for more details. Your feedback is appreciated.

== Installation ==
1. Download and extract WP Tweets zip file to the plugin folder. Verify that you have the wp-tweets folder right inside the plugin folder.
1. Activate WP Tweets from WordPress plugin administration page.
1. If you are using Widget system, add the WP Tweets as a widget. Configure twitter username, maximum tweets to display and title from the Widget properties tab.
1. If you embedding WP Tweets code, use &lt;?php show_wp_tweets('twitterusername',3,'');?&gt; in your theme file sidebar.
1. Customize appearance suitable for your theme by modifying wp-tweets.css file inside the plugin folder.  You can modify three style selectors - ul#wp_tweets_marker, ul#wp_tweets_marker li and ul#wp_tweets_marker li a. Following is the sample selector declaration that I use for my site. Note the use of !important to override default CSS inheritance rules.

ul#wp_tweets_marker li {

  border:0px 0px 0px 0px !important;

  font-weight: normal !important;

  background-image:none !important;

  background-position:0px 0px !important;

  padding:0px 0px 5px 10px !important;

  font-size:11px !important;

  font-family:Verdana !important;

  line-height:20px !important;

}

== Frequently Asked Questions ==

= The look and feel of tweet list is not what I wanted. How do I correct it? =

You need to manually edit the wp-tweets.css to match the display style with your theme. Please contact me if you need any help.

= Why no tweets are displayed when I activate the plugin? =

Ensure that you have set the twitter username, maximum count and title correctly. Also ensure that you have either added the widget or added the required code. Finally verify that your pages do not have a JavaScript error.

== Screenshots ==

1. WP Tweets in action.
2. Configuring WP Tweets from widget panel.
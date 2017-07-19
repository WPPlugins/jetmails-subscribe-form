=== Email Marketing Subscribe Form for JetMails.com ===
Contributors: jetmails
Tags: jetmails, email, newsletter, signup, marketing, plugin, widget
Author URI: http://www.jetmails.com/
Requires at least: 2.5
Tested up to: 2.9.2
Stable tag: 1.0.4

The jetMails plugin allows you to easily setup a subscribe form for your list.

== Description ==

The jetMails plugin allows you to easily setup a subscribe form for your list.

== Installation ==

This section describes how to install the plugin and get started using it.

1. Unzip our archive and upload the entire `jetmails-subscribe-form` directory to your `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to Settings and look for "JetMails Form Setup" in the menu
1. Enter your JetMails Username & Password and let the plugin verify them
1. Select One of your lists to have your visitors subscribe to.
1. Finally, go to Manage->Widgets and enable the widget
1. And you are DONE!

= Advanced =

If you have a custom coded sidebar or something else special going on where you can't simply enable the widget
through the Wordpress GUI, all you need to do is:

If you are using Wordpress v2.5 or higher, you can use the short-code:
` [jetmails_subscribe_form] `

If you are adding it inside a php code block, pop this in:

` jetmails_subscribe_form_display_widget(); `

Or, if you are dropping it in between a bunch of HTML, use this:

`<?php jetmails_subscribe_form_display_widget(); ?>`

Where ever you want it to show up. 

Note: in some environments you will need to install the Exec_PHP plugin to use that method of display. It can be found here: http://wordpress.org/extend/plugins/exec-php/


== Internationalization (i18n) ==

Currently we have the plugin configured so it can be easily translated and the following languages supported:

* en_US - English in the U.S.
* es_ES - Spanish in Spain

If your language is not listed above, feel free to create a translation. Here are the basic steps:

1. Copy "jetmails_i18n-en_US.po" to "jetmails_i18n-LANG_COUNTRY.po" - fill in LANG and COUNTRY with whatever you use for WPLANG in wp-config.php
2. Grab a transalation editor. [POedit](http://www.poedit.net/) works for us
3. Translate each line - if you need some context, just open up jetmails-subscribe-form.php and search for the line number or text
4. Send it to us - info@jetmails.com - and we'll test it and include it with our next release


== Frequently Asked Questions ==



== Screenshots ==


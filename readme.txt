=== Plugin Name ===
Contributors: kgajera
Tags: postform, form, contact form, email, recaptcha, akismet
Requires at least: 5.6
Tested up to: 5.6
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Save form submissions received using the Contact Form 7 plugin to Postform.

== Description ==

[Postform](https://postform.com) is a back-end platform for HTML forms that allows you to collect submissions and integrate with apps you already use. With this plugin, you can use Postform to process and save submissions from [Contact Form 7](https://wordpress.org/plugins/contact-form-7) forms. Beyond just collecting submissions, configure [Postform Plugins](https://postform.com/plugins) to send email notifications and configure other integrations.

This plugin does the following:

- When editing your Contact Form 7 form, there will be a "Postform" tab that will let you enter your Postform endpoint URL
- When using the Contact Form 7 shortcode to display the form, the form's `action` url will be replaced with Postform's endpoint URL

== Frequently Asked Questions ==

= Do I need to have a Postform account? =

Yes, you need to have a Postform account. Using your Postform account, you will be able to generate a unique endpoint for each of your forms to collect submissions.

= Do I need to have the Contact Form 7 plugin installed? =

Yes, this plugin is dependent on [Contact Form 7](https://wordpress.org/plugins/contact-form-7) and will not work without it.

= Will the mail and validation features of Contact Form 7 still work? =

No, you should be using [Postform Plugins](https://postform.com/plugins) to send email notifications and validate data.

= Can forms be submitted using AJAX? =

This plugin does not provide a way to submit forms using AJAX. However, you could add custom JavaScript to support this.

== Screenshots ==

1. Enter your Postform endpoint

=== Real User Monitoring by Pingdom ===

Contributors: Pingdom
Tags: pingdom, real user monitoring, rum, web performance
Requires at least: 2.1
Tested up to: 5.3
Stable tag: 1.0.4

With SolarWinds® Pingdom® real user monitoring you'll see how your website performs, how your users experience it, and what slows it down.

== Description ==

This simple plugin helps you add your Pingdom Real User Monitoring code snippet to the HEAD tag of your WordPress sites.

Once added, Pingdom immediately starts collecting data from your website's visitors. You can view all that collected data in your Pingdom control panel at <a href="https://my.pingdom.com" title="My Pingdom">my.pingdom.com</a>.

With Pingdom <a href=” https://www.pingdom.com/product/performance-monitoring/”>real user monitoring</a> you can know exactly how visitors are experiencing your website's performance. It provides invaluable insights into the website's load time, and also also helps answer questions like how your website truly performs from a specific device, in a specific country, from a specific web browser.

Real user monitoring is a way to see every single visitor and how they're experiencing your website in real time. It's paramount when you want to make improvements to your website's performance.

Please note you need a Pingdom account for this plugin. If you don't have one, grab one at <a href="https://www.pingdom.com/rum" title="Pingdom Real User Monitoring">pingdom.com</a>. It's super-easy!

== Installation ==

**Option 1**

1. From your WordPress administration interface, go to 'Plugins' > 'Add new'. Once there, search for "Pingdom" or "real user monitoring."
2. Click 'Install Now' and follow the instructions.
3. Now go to 'Plugins' > 'Pingdom Real User Monitoring'. There you will find further instructions for how to enable RUM on your WordPress site.

**Option 2**

1. Upload the full directory into your /wp-content/plugins directory
2. Activate the 'Pingdom Real User Monitoring' plugin from the 'Plugins' menu in WordPress
3. Now go to 'Plugins' > 'Pingdom Real User Monitoring'. There you'll find further instructions for how to enable RUM on your WordPress site.

== Frequently Asked Questions ==

**How does Pingdom collect the real usermonitoring data?**

Pingdom uses a JavaScript snippet that you place in the <head> tag of your HTML code to collect performance data from users visiting your site. The script is loaded asynchronously, so it doesn't affect site performance. The JavaScript snippet must be placed on any page you wish to collect data for.

You get your JavaScript snippet when creating a new Real User Monitoring check in our control panel.

Our JavaScript collects performance data using two main methods:

1.  <a href="http://www.w3.org/TR/navigation-timing/" title="W3C Navigation Timing">The Navigation Timing API</a> is used for newer browsers that support it (e.g. IE9+, Chrome and Firefox 10+).
2.  For browsers that does not support the Navigation Timing API, we utilize <a href="http://stevesouders.com/episodes/" title="Steve Souders Episodes">Episodes</a>.

**What makes Real User Monitoring different from Google Analytics?**

Our real user monitoring (RUM) is much more focused on performance than Google Analytics and many other sales-/site usage-oriented web analytics tools. This means in RUM, you'll see how your site performs, how the user experience is for your site, and what is slowing your site down, while in Google Analytics you'll see things like traffic sources and how users navigate your site.

In other words, real user monitoring is the perfect complement to your other web analytics tools.

**Are there any additional scripts downloaded?**

The JavaScript will download other scripts needed to gather your data asynchronously and does not affect the performance in any way.

**Does this capture any type of PII (Personally Identifiable Information)?**

No, we do not collect any PII-data and we don't store IP addresses (yes, we use the IP address to determine which country the visitor is from, but it's not stored). All data collected is merely that from the browser.

== Screenshots ==

1. Collect real performance data from your actual visitors across the globe with an incredibly simple setup.

2. View a list of top pages and their performance.

3. Drill down on specific page performance, including loading time, exit rates, and pageviews.

4. Filter by device, browser, or region.

6. To get started, simply add your Site ID in the WordPress admin panel.

== Changelog ==

**1.0.3**

*   This is the launch version.

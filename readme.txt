=== PS Auto Sitemap ===
Contributors: jim912
Tags: sitemap, post, page, seo, cms
Requires at least: 2.3.1
Tested up to: 2.7
Stable tag: trunk

Auto generator of a customizable and designed sitemap page.

== Description ==

"PS Auto Sitemap" is a plugin that **automatically generates a site map page from your WordPress site**. 

It is **easy to install for beginners** and **easy to customize for experts**.
It can change the settings of the display of the lists from administration page, **several neat CSS skins for the site map tree are prepared**.

When you use WordPress as CMS of the Web site, you can expect the **effect of SEO**, **improvement of the usability**, and so on.

= Functions of "PS Auto Sitemap": =
* Display/hide of particular home. 
* Display/hide of particular categories and posts. 
* Display/hide of pages. 
* Limitation of the depth of the list. 
* Set the display order of the page list and the post list.
* Set the excluded categories from the list. 
* Set the excluded posts and pages from the list. 
* Select the display style of the site map from 12 prepared designs (or no style).
* Use or not caching sitemap content.

= Version history =
* **1.1.0**
 * bug fix : post lists are displayed double in case of setting tags.
 * new function : Display/Hide home list
 * new function : caching sitemap content
 * add 2 sitemap styles.(optimised for dark backgroud color)
* **1.0.7**
 * reduce using memory.
* **1.0.6**
 * Bugfix : foreach error in case of all categories set as top level
* **1.0.5**
 * Added 5 preset styles( Label, Music, Arrows, Business, Index )
 * Bugfix : wrong URL of css file in windows server and windows local pc.
 * some code refactoring
* **1.0.0**
 * Public release
 
== Installation ==
1. Unzip the downloaded package and upload into your WordPress plugins directory.
If you use WordPress 2.7 or later, you can install from admin page.
2. Go to plugins list and activate "PS Auto Sitemap".
3. Post a page that will use as the sitemap page. 
4. Insert following code in the content area. (Use HTML mode) 	`<!-- SITEMAP CONTENT REPLACE POINT -->`
5. Define the sitemap's ID at "PostID of the sitemap" field of the setings.

== Frequently Asked Questions ==
= The sitemap does not appear. =
Check the page ID of the sitemap page.
Check the system code that you pasted.(Surely used HTML mode?)

When the sitemap is still not displayed, other plugins might be conflicts. de-activate the other plugins and check the sitemap page.
(If there are conflicted plugins, please tell us.)


= The selected style have collapsed. =
The CSS of using theme may be interfere in the selected style.
Select the style "no style" and write CSS yourself or use another themes.
Or, if you tell us the theme and your selected style, we might help you.

== Screenshots ==
1. Administration interface of PS Auto Sitemap
2. Preset sitemap styles.

== Links ==
"[PS Disable Auto Formatting](http://wordpress.org/extend/plugins/ps-disable-auto-formatting/ "WordPress editting support plugin")"Stops the automatic forming and the HTML tag removal in the html mode of WordPress, and generates a natural paragraph and changing line.

"[CMS service with WordPress](http://www.web-strategy.jp/ "CMS service with WordPress")" provides you service that uses WordPress as a CMS.

== Special Thanks ==
Translation:[dacelo](http://www.dacelo.info/blog/ "Translation")
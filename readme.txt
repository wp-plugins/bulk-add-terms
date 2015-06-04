=== Bulk Add Terms ===
Contributors: sohan5005
Tags: categories, admin, terms, taxonomy, tags, post
Requires at least: 3.0.0
Tested up to: 4.2.2
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A lightweight plugin to add thousands of taxonomy terms in one go.

== Description ==

Have you ever been frustrated adding more and more categories or tags or any other terms in a rush? Don't worry anymore. You can add thousands of terms in one go with this plugin.
## How do I do that?
1. Install the plugin and activate. A new menu called 'Add Bulk Terms' will pop up.
2. Click on the menu and you'll be taken to a new page where you will see all the registered taxonomy either by theme or any plugin.
3. First select a taxonomy which you want to add terms.
4. Then insert the terms in the right side textarea. Make sure each line contains only one term.
5. Click on 'Add Now' button. A little confirmation will pop up just to make sure you have inserted everything correctly. Click yes and BOOM. All terms are added.
## What about nesting parent and child?
This plugin supports to do that. You can go and do nesting. You can indent child levels with a dash (-). For example:
`
Foo
-Bar
-Baz
`
In the example above, 'foo' will be parent while 'bar' and 'baz' will be child of it.
You can use correct indent to make even more child of child. Example:
`
Foo
-Bar
--Baz
`
Complex nesting example:
`
Foo
-Child of Foo
--Grand child of Foo
-Second child of Foo
Baz is sibling of Foo
-Nephew of Foo
--Grand child of Baz
--Second grand child
-Son of Baz
-Daughter of Baz
I am a lonely term
Do not have child
`
Unfortunately the maximum supported level is as deep as the SEA.
## Features
* Unlimited terms per time
* Unlimited level of nesting
* Supports any registered taxonomy. (only those which can be added or removed within UI)
* Uses AJAX request
## Known issues
* Slugs are automatically generated.
* You can't add child items to those terms which are already added. If you try to do, the given parent item will add as a new term.

GitHub repository: https://github.com/sohan5005/bulk-add-terms


== Installation ==

1. Download the plugin zip file from the repository.
2. Upload the zip file directly from Plugins>Add New or extract and upload files to wp-contents/plugins/add-bulk-terms/ folder via FTP.
3. Activate the plugin.

== Frequently Asked Questions ==

= Which taxonomies are supported to add terms? =

You can add terms to any available taxonomies. However, if any registered taxonomy doesn't have an UI, it will be counted as something that should not be changed by you. So, you can't add terms to that taxonomy. For example, Nav menu's taxonomy is like that.

= Can I add child terms? =

Yes, the possible level is unlimited. Please see the description for example.

= Can I use this plugin in my commercial projects? =

Yes, you can do that. Attribution will be highly appreciated.

== Screenshots ==

1. This is the initial main screen of the plugin. On the left side all available taxonomies are listed. On the other hand, the textarea to add terms.

2. Here you have to select a taxonomy and add some terms. In this case, Category

3. You have to wait a few seconds after clicking Add Now button and watch for this notice on the bottom right corner.

4. Then check the Category manage screen and see the terms are added as you inserted.

5. The hot and fresh options page.

== Changelog ==

= 1.0 =

####Initial release

= 1.1 =

####Features update

* New options page added
* Now same terms can be added to multiple taxonomies
* Non-hierarchical taxonomies can be hidden from options
* Added option to keep the text after adding terms
* Some small bug fixes

== Upgrade Notice ==

The newest version has some new options added. Please update to check them out. If any issues found, please post on support section.
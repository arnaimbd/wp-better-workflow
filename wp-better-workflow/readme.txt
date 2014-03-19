=== GOOGLE MAPS ===
Contributors: jamesawesome
Tags: approval, workflow, admin, administration, dashboard, multisite
Requires at least: 3.0
Tested up to: 3.8.1
Stable tag: trunk 

== Description ==
WP Better Workflow is meant to create a workflow process in WordPress. This plugin adds a box to the post edit screen when a user does not have publish permissions for that post type. It also allows you to set a WordPress role as the approvers. Note: this role must have publish permissions. The approvers get notified by email when someone has submitted something to the workflow. This works on WordPress Multisite too.

**If you need help setting up the roles, I'd recommend the [Members plugin](http://wordpress.org/extend/plugins/members/ "Members plugin").**

== Screenshots ==
1. Added a checkbox to the edit page for submitting to the workflow.
2. WP Better Workflow dashboard. This shows all the items in the workflow.
3. Comparing the old and new pages.

== Installation ==
1. Copy the plugin files to <code>wp-content/plugins/</code>

2. Activate plugin from Plugins page or Network Activate for multisite

3. Go to Settings -> WP Better Workflow to adjust plugin settings

4. You must ensure the users you want to approve are in a role that does not have publish_page (or any publish permissions for other post types) permissions.

== Changelog ==
= 1.0 =
* Initial release
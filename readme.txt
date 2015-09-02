=== Admin Menu ===
Contributors: Denis-de-Bernardy, Mike_Koepke
Donate link: https://www.semiologic.com/donate/
Tags: admin-menu, admin, cms, semiologic
Requires at least: 3.3
Tested up to: 4.0
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


The admin menu plugin for WordPress sticks key admin menu links to the top of your blog's screen.


== Description ==

> *This plugin has been retired.  No further development will occur on it.*  With a menu bar built into WordPress and the fact other plugins hook into that, this plugin conflicts with that capability


The admin menu plugin for WordPress sticks key admin menu links to the top of your blog's screen.

The menu will automatically appear to the top of your blog. Menu items will only be visible when relevant.

It's quite useful for those who run their WP install as a CMS. When you create a static page using its New Page link, it will also set the new page's parent automatically, to the ongoing page.

= Hat Translators =

- Spanish: Andrew [WebHostingHub](http://www.webhostinghub.com/)

= Help Me! =

No further support is provided.


== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress


== Screenshots ==

1. Admin Menu in action


== Frequently Asked Questions ==

= It Doesn't Work =

Make sure your theme has the following in between its `<body>` and `</body>` tags:

    <?php wp_footer(); ?>


= Hiding the Admin Menu to Visitors =

The admin menu will not display to visitors unless you specifically want this to occur.

To configure the behavior, browse Settings / Admin Menu.


== Change Log ==

= 6.7.1 =

- Development has ceased on this plugin.  Updated source and readme accordingly

= 6.7 =

- WP 4.0 compat

= 6.6.1 =

- Re-release due to svn glitch

= 6.6 =

- Don't display the frontend admin menu bar for a wordPress detected mobile site.

= 6.5.2 =

- Fix php warning message regarding sem_admin_menu_admin

= 6.5.1 =

- Fix localization

= 6.5 =

- Code refactoring
- WP 3.9 compat

= 6.4.1 =

- Spanish files missing in checkin.   Re-release.

= 6.4 =

- Added spanish translations.
- WP 3.8 compat

= 6.3 =

- WP 3.6 compat
- PHP 5.4 compat

= 6.2.1 = 

- Fix width of toolbar on IOS devices

= 6.2 =

- Login and Register links are set to nofollow now.

= 6.1.1 =

- Fix svn versioning issue

= 6.1 =

- Fixed disabling of WordPress admin bar in WP 3.3+
- WP 3.5 compat
- Replace deprecated functions

= 6.0.5 =

- Kill the WP 3.1 admin bar when the plugin is active.

= 6.0.4 =

- Optimization when the always-on option isn't turned on.

= 6.0.3 =

- WP 3.0.1 compat

= 6.0.2 =

- More WP 3.0 fixes

= 6.0.1 =

- WP 3.0 compat

= 6.0 =

- login/logout now do their best to redirect you to where wherever you were
- Drop broken WPMU support
- Full localization
- Code enhancements and optimizations

=== Tumblr Feed ===
Contributors: theAlpinePress, Pomelo Productions
Tags: photos, photostream, stylish, pictures, images, widget, sidebar, gallery, lightbox, fancybox, colorbox
Requires at least: 2.8
Tested up to: 4.9.8
Stable tag: 0.2.0
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Stylish and compact plugin for displaying Tumblr images in a sidebar, post, or page. 

== Description ==

This is a clone of the [Alpine PhotoTile](https://wordpress.org/plugins/alpine-photo-tile-for-tumblr/) plugin updated to support modern versions of PHP and WordPress.

Retrieve photos from a Tumblr user, custom Tumblr URL, or tag with the Alpine PhotoTile for Tumblr. The photos can be linked to the your Tumblr page, a specific URL, or to a Lightbox slideshow. Also, the Shortcode Generator makes it easy to insert the widget into posts without learning any of the code. This lightweight but powerful widget takes advantage of WordPress's built in JQuery scripts to create a sleek presentation that I hope you will like. A full description and demonstration is available at [the Alpine Press](http://thealpinepress.com/alpine-phototile-for-tumblr/ "Plugin Demo").

**Features:**

* Display Tumblr images in a sidebar, post, or page
* Multiple styles to allow for customization
* Lighbox feature for interactive slideshow (Fancybox, or ColorBox)
* Simple instructions
* Widget & shortcode options
* Feed caching/storage for improved page loading

**Quick Start Guide**

1. After installing the plugin on your WordPress site, make sure it is activated by logging into your admin area and going to Plugins in the left menu.
2. To add the plugin to a sidebar, go to Appearance->Widgets in the left menu.
3. Find the rectangle labeled Alpine PhotoTile for Tumblr. Click and drag the rectangle to one of the sidebar containers on the right.
4. Once you drop the rectangle in a sidebar area, it should open to reveal a menu of options. The only required information for the plugin to work is Tumblr ID. Enter this ID and click save in the right bottom corner of the menu.
5. Open another page/window in your web browser and navigate to your WordPress site to see how the sidebar looks with the Alpine PhotoTile for Tumblr included.
6. Play around with the various styles and options to find what works best for your site.

== Installation ==

1. Upload `alpine-photo-tile-for-tumblr` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the widget like any other widget.
4. Customize based on your preference.

== Frequently Asked Questions ==

**I'm getting the message "Tumblr feed was successfully retrieved, but no photos found". What does that mean?**

This message simply means that while no distinguishable errors occurred, the plugin found your feed to be empty.

**I'm getting the message "Tumblr feed not found. Please recheck your ID". What does that mean?**

This message can mean two things. First, it can indicate that the username or custom url were input incorrectly, causing the feed to fail. In this case, you should try to correct and re-save your IDs.

Second, this message can also mean that the server your WordPress site is being hosted on has prevented the feed from being retrieved. While it is rare, we have encountered web-hosts that disable the feed fetching functions used in the PhotoTile plugin. If this is the case, there is nothing we can do to override or work around the settings on your host server.

**Is there a shortcode function?**

Yes, rather than explaining how to setup the shortcode, I've created a method of generating the shortcode. Check out the Shortcode Generator on the plugin's settings page ( Settings->AlpineTile: Tumblr->Shortcode Generator).

**Why doesn't the widget show my most recent photos?**

The plugin caches or stores the Tumblr feed for three hours. If the new photos have still not appeared after this time, it is possible that Tumblr is responsible for the delay. While Tumblr is fairly prompt about updating photo feeds, periods of high traffic (especially on weekdays between 10am and 4pm) can cause a delay in feed updates.

**Can I show more than 20 photos?**

Yes, as of version 1.2.0, up to 100 photos can be retrieved and displayed.

If you have any more questions, please leave a message at [the Alpine Press](http://thealpinepress.com/alpine-phototile-for-tumblr/ "Plugin Demo").

I am a one-man development team and I distribute these plugins for free, so please be patient with me.

== Changelog ==

= 1.0.0 =
* First Release

= TODO =
* Rebuild the entire plugin
** Rebuild the displays to use templates
** Remove jQuery dependency
** Make displays dynamic
** Add Test Coverage
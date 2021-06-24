# Install & Setup [WordPress](http://wordpress.org) 

Author: [Anas Labzar](https://github.com/AnasLabzar)

##  How To Install WordPress 

## Synopsis

I was looking around for a useful script to speed up the setting-up process for a WordPress site.

After looking around, I found a couple of great scripts by [@snaptortoise](https://github.com/snaptortoise) and [@darlanrod](https://github.com/darlanrod). However I needed more features to speed up my day-to-day WordPress work, so I built on top of the fantastic work these guys did to get it to where I needed it to be.


# Installation

I keep this script on my server so that I can start an up-to-date WordPress project almost anywhere, along with the plugins I enjoy and am used to working with.  It's hosted here on GitHub, so I can execute this from the terminal by typing:

`curl https://raw.github.com/snaptortoise/wordpress-quick-install/master/wordpress | sh`

It will download the latest version of WordPress, along with the latest version of all the plugins listed at the end of this README doc, and install them to the current directory.  I find it saves time.

Alternatively, you can make the `wordpress`  file executable and keep it somewhere in your `$PATH` if you're rather keep it local.

Plugin List
-----------
- All-in-One-SEO-Pack
- Sitemap Generator
- Secure WordPress
- Hierarchy Plugin
- Image Widgets (Why isn't this standard?)
- Super-cache
- W3 Total Cache (A little redundant with above, but hey, I like options.)
- Register Plus Redux (Good for membership-style sites)
- Regenerate Thumbnails (good for when you need to change custom thumb sizes late in a project)
- Taxonomy Taxi
- Custom Post Type UI 
- WordPress Importer
- Password Protect WordPress
- WP-Quick-Pages
- FeedWordPress
- BackWPup
- [Meta Box](http://wordpress.org/plugins/meta-box/)
- [Options Framework](http://wordpress.org/plugins/options-framework/)



## Plugins
The script installs the following WordPress plugins:

Advanced Custom Fields †
ACF Content Analysis for Yoast SEO
Contact Form 7
Flamingo
W3 Total Cache
Wordfence Security
Yoast SEO
† I highly recommend purchasing the Pro version!

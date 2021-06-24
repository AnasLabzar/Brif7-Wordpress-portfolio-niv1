# Install & Setup [WordPress](http://wordpress.org) 

Author: [Anas Labzar](https://github.com/AnasLabzar)

##  How To Install WordPress 

## Synopsis

I was looking around for a useful script to speed up the setting-up process for a WordPress site.

After looking around, I found a couple of great scripts by @snaptortoise (https://github.com/snaptortoise) and @darlanrod (https://github.com/darlanrod). However I needed more features to speed up my day-to-day WordPress work, so I built on top of the fantastic work these guys did to get it to where I needed it to be.


# Installation
cd into the project root and run the following in command-line:

curl -O https://raw.githubusercontent.com/jasewarner/wordpress-installer/master/wordpress.sh

Then run the script: sh ./wordpress.sh

It will download the latest version of WordPress, along with the latest version of all the plugins listed in the shell script and install them to the current directory, as well as the boilerplate theme.

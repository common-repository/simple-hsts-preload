=== Simple HSTS Preload ===
Contributors: kevinhq
Tags: security, hsts
Requires at least: 4.9
Tested up to: 5.2.2
Stable tag: 1.1


This plugin enables HSTS header on WordPress


== Description ==

This plugin enables WordPress to send HSTS header to browser

IMPORTANT NOTE: This plugin won't work if you use any WordPress caching plugin. If this is the case, then update your .htaccess file to specify HSTS header.

HTTP Strict Transport Security (HSTS) is a web security policy mechanism that helps to protect websites against protocol downgrade attacks and cookie hijacking. 

It allows web servers to declare that web browsers (or other complying user agents) should interact with it using only secure HTTPS connections, and never via the insecure HTTP protocol


== Installation ==

After you've downloaded and extracted the files:

1. Upload the complete 'simple-hsts-preload' folder to the '/wp-content/plugins/' directory OR install via the plugin installer
2. Activate the plugin through the 'Plugins' menu in WordPress
3. And you are done!


== Changelog ==

= 1.0 =
* Enable HSTS Header, to submit to https://hstspreload.org/
* Initial release

= 1.1 =
* Test with WordPress 5.2.2
* Update documentation

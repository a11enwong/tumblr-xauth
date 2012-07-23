XAuth-Tumblr
============

Basic XAuth for Tumbr. Authorizes then retrieves the user's data. Sources acknowledged within.

This is an extremely simple tumblr client for Mac OS X and iOS, which
uses xauth for authentication.

See tumblr-xauth.m for example usage. Fill in values for
CONSUMER_KEY, CONSUMER_SECRET, TUMBLR_USERNAME, and
TUMBLR_PASSWORD. Compiles on Mac OS X using gnu make.

This code is possible thanks to documentation and code examples found
on the following websites:

http://weblog.bluedonkey.org/?p=959
http://cocoawithlove.com/2009/06/base64-encoding-options-on-mac-and.html
http://www.getsharekit.com/
http://www.gigliwood.com/weblog/Cocoa/Q__When_is_an_conne.html
http://dev.twitter.com/pages/xauth
http://dev.twitter.com/doc/post/oauth/access_token
http://dev.twitter.com/pages/auth#auth-request

Special thanks to Matt Gallagher of cocoawithlove.com for providing an
Objective-C implementation of Base64 encoding for Mac and iPhone.

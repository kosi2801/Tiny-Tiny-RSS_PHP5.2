Tiny Tiny RSS - backward compatibility patch
=============

This is a clone of [Tiny Tiny RSS][1], a web-based news feed aggregator. 
The purpose of this clone is to lower the installation requirements so that 
Tiny Tiny RSS can also be installed and used on webservers or hosting
solutions which do not meet the original Tiny Tiny RSS requirements.

## Changes

Currently the source is functional identical to [Tiny Tiny RSS 1.7.8][2] but
with patches to work with following relaxed requirements compared to the 
[original PHP requirements][3]:

* PHP 5.2
* open_basedir restriction supported

Bugs/Issues

* One Time Passwords are currently disabled because compatibility issues with PHP 5.2

## Installation

Installation is identical to the [original installation][4] apart from the lower
requirements laid out above.

## Credits, License, Copyright

Of course all credit for Tiny Tiny RSS, apart from my patches, goes to
Andrew Dolgov.
Copyright for original Tiny Tiny RSS is (c) Andrew Dolgov.

Licensed under GNU GPL version 2.

[1]: http://tt-rss.org
[2]: https://github.com/gothfox/Tiny-Tiny-RSS/tree/1.7.8
[3]: http://tt-rss.org/redmine/projects/tt-rss/wiki/PhpCompatibilityNotes
[4]: http://tt-rss.org/wiki/InstallationNotes
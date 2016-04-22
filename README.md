HTML Purifier
=============

HTML Purifier is an HTML filtering solution that uses a unique combination
of robust whitelists and agressive parsing to ensure that not only are
XSS attacks thwarted, but the resulting HTML is standards compliant.

HTML Purifier is oriented towards richly formatted documents from
untrusted sources that require CSS and a full tag-set.  This library can
be configured to accept a more restrictive set of tags, but it won't be
as efficient as more bare-bones parsers. It will, however, do the job
right, which may be more important.

HTML Purifier can be found on the web at: http://htmlpurifier.org/

## Standalone version

For those of you who balk at the possibility of a 100+ includes, we also offer a conveniently packaged single-file version of HTML Purifier. Well, not really, since HTML Purifier does require some auxiliary files in order to work (but they are neatly tucked away in a folder named standalone). Include HTMLPurifier.standalone.php and be done with it!

## Installation

Package available on [Composer](https://packagist.org/packages/masterjoa/htmlpurifier-standalone).

If you're using Composer to manage dependencies, you can use

    $ composer require "masterjoa/htmlpurifier-standalone": "dev-master"
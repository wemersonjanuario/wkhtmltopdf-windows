wkhtmltopdf-windows
================

This Repo contains the Windows (MSVC 2013) Binaries for Windows Vista or later; bundles VC++ Runtime 2013.
[wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.2.1'.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for Windows with:

    php composer.phar require wemersonjanuario/wkhtmltopdf-windows "0.12.2.1"


The binaries will then be located at:

    vendor/wemersonjanuario/wkhtmltopdf-windows/bin/wkhtmltopdf-windows

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-32bit.exe.bat and vendor/bin/wkhtmltopdf-64bit.exe.bat
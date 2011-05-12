ARM EABI Toolchain Builder
==========================

A fork of jsnyder's [arm-eabi-toolchain](https://github.com/jsnyder/arm-eabi-toolchain).

Tested on Mac OS X 10.6.


Instructions
------------
To install the toolchain:

> make install

To remove previous build, after a failed install perhaps:

> make clean

Installation path is set by the PREFIX variable in Makefile.

Add $(PREFIX)/bin to the PATH environment variable in your profile startup script (.bash_profile, .profile etc), for permanent shell access to the installed binaries.  For example:

> export PATH=/usr/local/sourcery/2011.03/bin:$PATH


Requirements
------------

Apple Developer Tools - required for GCC, make and binutils: [here](http://developer.apple.com/Tools/).

[Homebrew](https://github.com/mxcl/homebrew) - required for pre-installation of libmpc, gmp, mpfr libraries.


History
-------
2011-04-11		Forked and updated to use Homebrew for dependencies
2011-05-12		Updated to Sourcery G++ Lite 2011.03-42

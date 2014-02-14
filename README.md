# Glib::JSON - Perl bindings for JSON-GLib

Glib::JSON is a Perl module providing access to the [JSON-GLib][0] C library
through the introspection data provided by the library itself, and the Perl
Glib::Object::Introspection module.

## Requirements

### Perl modules

 * Glib
 * Glib::Object::Introspection
 * Glib::IO
 * Test::Simple

### C libraries

 * GLib
 * JSON-GLib

## Building Glib::JSON

In order to build from Glib::JSON from Git you will need the [dzil][1] tool
of the Dist::Zilla Perl module installed and available.

### Cloning

    $ git clone https://github.com/ebassi/perl-Glib-JSON
    $ cd perl-Glib-JSON

### Building

    $ dzil build
    $ dzil test
    $ dzil install

## Using Glib::JSON

Simply import Glib::JSON in your Perl script or module:

    use Glib::JSON;

Yes, that's it.

## Copyright and license

Copyright &copy; 2014  Emmanuele Bassi

This library is free software; you can redistribute it and/or modify it under
the terms of the GNU Library General Public License as published by the Free
Software Foundation; either version 2.1 of the License, or (at your option) any
later version.

This library is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.

See the LICENSE file in the top-level directory of this distribution for the
full license terms.

[0]: https://wiki.gnome.org/Projects/JsonGlib
[1]: http://dzil.org/

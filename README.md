# set_conf Tool

A simple CLI wrapper for [configparser](https://github.com/python/cpython/blob/3.8/Lib/configparser.py) library.
Made for use at command line / bash to manipulate config files.
Built to set values in .INI files (or alike, e.g. some .CONF files), which are delimited by '=' instead of ' = '.
Inspired by [crudini's](https://github.com/pixelb/crudini) disability to write ini-files without ' = ' spaces.

### Usage:

Simply clone or download this repo.
Make sure, [Python3](https://www.python.org/) is installed and properly configured.
From CLI, run it like this: 

    $ python3 set_conf.py <filename.conf> <section> <option> <new_value>

or this (given, everything is well-configured):

    $ ./set_conf.py <filename.conf> <section> <option> <new_value>

### Example:

    $ ./set_conf.py myfilename.conf mysection myoption 42


unruu
=====

unruu is a simple command line utility to extract the rom.zip file from a 
HTC RUU update executable.

Please note that it'll output the rom.zip file to your current directory.

Requirements (libunshield v0.9 or higher):
------------------------------------------

    $ git clone https://github.com/twogood/unshield.git
    $ cd unshield/
    $ ./bootstrap
    $ ./configure --prefix=/usr
    $ make
    $ sudo make install

Building:
---------

    $ ./autogen.sh
    $ ./configure
    $ make

Downloading:
------------

You can download pre-compiled snapshots or releases from:-

* http://psi.kennynet.co.uk/unruu/

Installing:
-----------

    $ sudo make install

Using:
------

    $ unruu /path/to/RUU.exe

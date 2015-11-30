Prerequisites
-------------
PyQt5 installed into system python, on Linux, Windows or OSX.

In virtualenv
-------------

Make sure pip and setuptools are up to date

(my-virtualenv) $ pip install -U pip setuptools

Allow virtualenv to access PyQt5

(my-virtualenv) $ pip install vext.pyqt5


Caveats
-------

Qt5 on Ubuntu seems to only be available for python3, which at the time of
writing is not supported by vext.  [Dec 2015]

Reporting Bugs
--------------

Report bugs to the [vext project](//github.com/stuaxo/vext/issues)


This is *Experimental* I haven't used PyQt5 much, feedback, patches welcome :)

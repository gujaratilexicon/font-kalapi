font-kalapi
===========

Kalapi Gujarati Unicode font.

Sample Text
===========

Run:

```
make test
```

to get sample output of Kalapi font.

Installation
============

#### Linux (using package)
In Debian and derivative distributions like Ubuntu, simply use:

```
sudo apt-get install fonts-aakar
```

#### Linux (manual installation)

Place font file to /usr/share/fonts folder and run,

```
fc-cache -v
```

in terminal.

#### Mac
```
wget -c https://github.com/gujaratilexicon/font-kalapi/archive/1.0.tar.gz
tar xvzf 1.0.tar.gz
cp Kalapi.ttf /Library/Fonts/Kalapi.ttf
```

#### Windows
TODO

How to generate TTF file?
=========================

For Linux (or any UNIX like systems or Mac OS X):

1. Install fontforge:

You need to have FontForge installed. See: <http://fontforge.sourceforge.net/>

2. Run make using:
```
make
```

License
=======
SIL OFL 1.1

Known Issues
============
See [pending issues] (https://github.com/gujaratilexicon/font-kalapi/issues)

Contact
=======

* Troubles/Bugs/Issues? please use Github issue tracker at:
  <https://github.com/gujaratilexicon/font-kalapi/issues>

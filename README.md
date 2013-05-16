dpwelib
=======

Legacy dpwe library, written in C, mainly used for sound file I/O in a number of tools from ICSI

2013-05-16 - Moved to githib at https://github.com/dpwe/dpwelib



ORIGINAL README FOLLOWS:

README for dpwelib - a utility library, mainly for audio and soundfiles.

1997feb17 Dan Ellis <dpwe@icsi.berkeley.edu>

******
To the extent possible under law, the author(s) have dedicated all
copyright and related and neighboring rights to this software to the
public domain worldwide. 

This software is distributed without any warranty.  

You should have received a copy of the CC0 Public Domain Dedication
along with this software. If not, see
<http://creativecommons.org/publicdomain/zero/1.0/>.
******

This directory contains a variety of sound-processing libraries and 
applications.  They include:

sndf	- a low-level multi-format soundfile interface library
snd	- a higher-level integrated interface to sndf soundfiles
audIO	- a portable audio hardware input/output interface library

sndplay   - a simple soundfile play program
sndrecord - a simple program for recording soundfiles from audio hardware
sndcmp    - for gathering statistics on a soundfile, or the difference 
	    between two soundfiles.
sndrfmt   - change the format (sample type, number of channels) of a soundfile.
sndrsmp   - change the sampling rate (resample/interpolate) a soundfile.

Each component has its own man page (e.g. sndf.man).

The package is configured by GNU Autoconf ("just type ./configure") and 
has been compiled on the following platforms:

sparc-sun-sunos4.1.3	(gcc 2.7.1)
sparc-sun-solaris2.5	(/opt/SUNWspro/SC4.0/bin/cc)
mips-sgi-irix5.3	(/usr/bin/cc)
mips-sgi-irix6.2	(/usr/bin/cc)
alpha-dec-osf4.0	(/usr/bin/cc)	audio input not yet supported
i586-unknown-linux	(gcc 2.7.2)	no simultaneous audio read & write
i686-unknown-linux	(gcc 2.7.2.1)		- '' -

The homepage for this package (for information on the latest version) is:

    http://www.icsi.berkeley.edu/~dpwe/dpwelib.html

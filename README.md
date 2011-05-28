jsstyle
==============

Overview
--------

jsstyle is a style checker for JavaScript coding style.  This tool is derived
from the cstyle tool used to check for the style used in the Solaris kernel,
sometimes known as "Bill Joy Normal Form".  This tools is not configurable.
It enforces a single coding style based on that cstyle.

The original cstyle tool can be found here:

http://cvs.opensolaris.org/source/xref/onnv/onnv-gate/usr/src/tools/scripts/cstyle.pl

The document describing C Style is available here:

http://www.cis.upenn.edu/~lee/06cse480/data/cstyle.ms.pdf


Status
------

No known bugs.  No new features planned.


Usage
-----

    # jsstyle file1.js [file2.js ...]

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

Examples of conditions checked by this tool include:
* Strings must be quoted with single quotes.
* Blocks must be indented with tabs, not spaces.
* Continuation lines must be indented with 4 spaces.
* Keywords (for, if, function, etc.) must be followed with a space.
* One line cannot contain multiple keywords.
* Relational operators must be surrounded with spaces.
* There must be no spaces between tabs, nor tabs between spaces.
* Lines must not end with whitespace.
* Multi-line block comments must start and end with a blank line.
* Return expressions must be parenthesized.

Status
------

No known bugs.  No new features planned.


Usage
-----

    # jsstyle file1.js [file2.js ...]

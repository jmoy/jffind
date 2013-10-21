jffind is a tool for finding files whose names contain 
certain keywords.

It tries to be clever in handling capitalisation and 
accents.

USAGE
------

    jffind <directory> <keyword> ...

It prints out the full path of files in `<directory>` and 
its subdirectories that contain `<keyword>`s in the file name. 

Only files with extension in the `EXT_WHITELIST` set hardcoded
in the program are printed. Currently the extensions
accepted are PDF, DJVU and DJV.

The entire directory tree is scanned each time the program 
is run.

DEPENDENCIES
-------------
jffind is written in Python and uses the PyICU library.

LICENSE
--------
GPL

MAINTAINER
-----------
Please send comments to jyotirmoy@jyotirmoy.net


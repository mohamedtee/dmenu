dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.

**Applied patches**
------------------
* dmenu-caseinsensitive-20200523-db6093f.diff
* dmenu-fuzzyhighlight-4.9.diff
* dmenu-fuzzymatch-4.9.diff
* dmenu-lineheight-4.9.diff
* dmenu-linesbelowprompt-and-fullwidth-20211014.diff
* dmenu-managed-4.9.diff
* dmenu-password-4.9.diff
* dmenu-xyw-5.0.diff

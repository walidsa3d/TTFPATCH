
TTFPATCH v1.0 - (C) by Wolfram Esser [wok@derwok.de] 2001-02-23

Provides an easy way for font designers to set the 'embeddable' flags
of their own true type fonts. If you want to prohibit embedding of your
font e.g. in Acrobat PDF files, simply run: 'ttfpatch myfont.ttf 2'

Usage: ttfpatch TrueTypeFontFile [NewFsTypeValue]

fsType values:
       0: embedding for permanent installation
       1: reserved - do not use!
       2: embedding restricted (not allowed!)
       4: embedding for preview & printing allowed
       8: embedding for editing allowed

http://www.derwok.de

WARNING!!!
----------
THE PROGRAM DIRECTLY CHANGES THE FILE (NO TEMPFILE OR DIFFERENT OUTFILE!)
IT MAY BE POSSIBLE (THOUGH UNLIKELY) THAT YOUR FONTFILE IS DESTROYED
AFER USING THIS PROGRAM. SO KEEP A BACKUP OF THE FILE TO BE MODIFIED!!!

This programm and ist sourcecode are freeware. 
You may do everything you want with the source / binary, as long
as you keep my (C)opyright notice unchanged.

DISCLAIMER - This program is freeware AND IS PROVIDED "AS IS" AND WITHOUT ANY EXPRESS 
OR IMPLIED WARRANTIES, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTIES OF 
MERCHANTIBILITY AND FITNESS FOR A PARTICULAR PURPOSE. IF YOUR LOCALITY DOES NOT 
ALLOW THESE WARRANTY CONDITIONS, YOU ARE NOT GRANTED PERMISSION TO USE.


TrueType Font, TTF and Microsoft are registered trademarks of Microsoft Corp.
Adobe, Acrobat, PDF are registered trademarks of Acrobat Corp.


Wuerzburg, Germany 2001-02-23


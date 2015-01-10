jpgMv
=====
jpgMv renames a collection of JPG files so they have
names like 2005-10-13_00.jpg or 2005-10-13+15-15-46_00.jpg

jpgMv is particularly useful when merging many photos into one directory;
it does not overwrite existing files.

jpgDate
=======
jpgDate gets the date, or date and time from a JPG.
jpgDate uses perl-Image-ExifTool.

It used to use the identify command from ImageMagic but I am now running
an old version of ImageMagic and identify does not work after using:
"convert -rotate ..." on a JPG.

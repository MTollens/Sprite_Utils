# Sprite_Utils
A simple Python script for making sprite sheets, created to assist in making Factorio sprite sheets
intended use case:
you have a bunch of loose sprites in order [000.png, 001.png .... 256.png]
and you need them all in one image, the standard method of sprite reading for 2d games
often games will impose limitations on the dimensions of the sprite sheets, so this can help you decide how many sprites per sheet
and how many sheets to make

Written to avoid using online sprite stitchers, since they usually provide limited control over dimensions and ouputs.

#FEATURES:
- convert entire contents of directory into clean sprite sheets
- define number of rows per sheet
- define number of columns per sheet
- define number of output files for input sprite set
- assists in reccomending number of output files

Requires PIL for image processing

install PIL or PILLOW (fork) to use 
(original PIL seems to be abandoned as of now)

windows:
py -m pip install PILLOW

Linux:
$pip3 install PILLOW

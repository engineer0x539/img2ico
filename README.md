                               img2ico
___________________________________________________________________________________________
Version 0.2.0.00229

Tool to create an icon, cursor, or animated cursor file from a directory of images.

Use your favorite image editing program to create the icons, then put them in a convenient
container using the img2ico tool.

The default settings will create an icon using images found in the selected directory.
The maximum size for path variables is 192 characters (via command line)
The maximum size for name variables is 64 characters (including config file)
The maximum size for icons is 256 by 256, and 32-bit color.

Transparency Masks are not currently supported in BMP files.  The compiled EXE only works
with files named "0.bmp" in the EXE directory for now.  This will change when the command
line is fully supported (Version 0.3.0).

Only one cursor hotspot per file is supported (this may change if there is a need for more
than one cursor per file).

Mipmap generation will make all file sizes starting with the initial size down on the list
below (m for mipmap):

          SIZE
       m  256x256
       m  128x128
       m  96x96
       m  64x64
       m  48x48
       m  32x32
       m  16x16
       m  8x8

	   Color Depth
	   m  32-bpp
	   m  16-bpp
	   m  8-bpp (256-color)
	      4-bpp (16-color)
		  1-bpp (monochrome)

A way to control mipmap generation will be added later.

___________________________________________________________________________________________

Special thanks to all those who provided data on the file formats above.
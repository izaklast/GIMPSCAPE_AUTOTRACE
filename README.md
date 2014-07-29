GIMPSCAPE_AUTOTRACE
===================

GIMP to INKSCAPE Auto Trace Bitmap
While editing a pic in GIMP, one-click function to auto trace Bitmap in Inkscape with last used settings.

Issues:
1. Settings stored or set manually for each session?
2. Auto detect changes in GIMP and disable trigger unless changes made?



GIMP SIDE:

1. #check for file save yes/no
2. #File save using to previous file location 
3. #initiate INKSCAPE trigger

INKSCAPE SIDE:

1. #trigger detected (open Inkscape if not running)
2. #pull file from save location
3. #delete currenet selection in worksapce
4. #import saved file into workspace
5. #select image in worspace
6. #initiate trace bitmap script
7. #retrieve last used settings
8. #apply trace to current selection
9. #close trace bitmap
10.#select new vectors for review

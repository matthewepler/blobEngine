blobEngine
==========

*A Processing app for customized blob detection on a series of images. 
*Matthew Epler, 2013

Dependencies
------------
Only works with Processing 1.5 for now.
ControlP5 v1.5.2
OpenCV 1.1 (the library provided by Processing 1.5 for OpenCV functions)

How To
------

At the top of setup(), replace the path string with the absolute path to your project's data folder. You will need to create this folder yourself if it doesn't already exist.

Paste your image files inside the data folder. If everything is in the right place, you'll get a success message in the console.

Adjust the settings and choose an export method. Note that the Image size, x, and y settings will not be used when exporting. These values only affect the image as it appears inside the GUI.

Notes
-----
This is in alpha and will need a lot of improvement. Please submit request for feature changes and/or additions in the Issues tab for this repo.

THere is currently no library for OpenCV that is compatible with Processing 2 and the latest version of OpenCV. I plan on updating this upon release of Greg Borenstein's upcoming wrapper for the latest OpenCV, which will be compatible with Processing 2.

Contact
-------
matthewepler@gmail.com
http://mepler.com



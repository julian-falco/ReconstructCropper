# GuidedReconstructCropper

This program is intended for use with the RECONSTRUCT software developed by the Harris Lab.

Given a specific object within a series of section images, the program will create a new set of files with the images cropped around the object.
The intention for this program is to cut time on loading images in the RECONSTRUCT software; the cropped section images will take less time to load.

New traces made on these files can be merged back to the original set of files.
The program also has a built-in function to restore the set of files to the original settings with the new traces.

To use this program, you will need to have Python installed on your computer.
Ensure that the Pillow and opencv-python modules are installed on your computer.
To do this open the command prompt on your computer (type CMD in the search bar) and type in the following:

pip install Pillow

pip install opencv-python

At this point, you should be able to download and run the python file.

You will need to provide directory paths for both the series and an empty folder to contain the new series files.
To get these, you can access the folders in your file explorer and copy the "link" at the top.

The program will ask for the name of the object the crop should be centered on. Ensure that the object name is correct, as the program is case-sensitive.
As for the radius around the crop, 5 microns works best for dendrite analysis.

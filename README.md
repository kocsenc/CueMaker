# CueMaker

CueMaker scans directories and creates .cue files for .bin files that are missing them. 
This is in response to RetroPie 4.x requiring the .cue file for psx games. There are some existing applications, 
however they require you to do each file individually.

This project consists of two applications.

## .Net
If you would like to create the files before you tranfer them you and are running windows, you can choose the .Net
application. It is a windows form application that doesn't need to be installed. Simply run the exe and select the 
folder or .bin that you want to create a .cue file for.

## Python
If you are on mac/linux or on the RetroPie you can use the python script. It will prompt you for the path you would
like to scan and create all the missing .cue files. It will also ask you if you want to scan recursively. It should
default to the correct directories for RetroPie.

## Release
Im having trouble getting github to accept a zip file on the releases, so for now you can grab them here:

Python:
https://github.com/thorst/CueMaker/blob/master/CueMaker/CueMakerPy2/CueMakerPy2.py

.Net:
https://github.com/thorst/CueMaker/blob/master/CueMaker/CueMakerDotNet/bin/Release/CueMakerDotNet.exe
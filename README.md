# Image-Z-Stack-and-Video-analysisis-with-Fiji

A script that navigates through folders and subfolders of a starting point, miming the folder structure at a given output path, and opening all files with a defined suffix for further analysis. The analysis separates microscopy input into separate channels, merges and saves them with a naming scheme that can be adjusted in the code. The script detects automatically, whether the given file is a image, z-stack or video and will adjust analysis accordingly. Just try it out on your microscopy images and see the magic happen.

## Naviagtion
The main scripts are found in [src/main/ijAnalysis.microscopy](src/main/ijAnalysis.microscopy) and [src/resources/ijAnalysis.microscopy](src/resources/ijAnalysis.microscopy).
- Analyzer.java
- Analyzer.ijm

## Installation
Just download the `.ijm` / `.java` files or clone the repository with a method to your liking.

## Application
I prefer opening Fiji and then navigating to `Plugins -> Macros -> Edit`. Then click on `File -> Open` and select the file. After that just click `Run` or select `Run -> Run` in the upper menu.

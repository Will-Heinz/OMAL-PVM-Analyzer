# OMAL-PVM-Analyzer

## Introduction
The OMAL PVM Analyzer software processes and analyzes polarization video microscopy time lapse data to determine the transition times and durations of ligand-induced lattice transitions in biomacromolecular crystals. The analysis is based on changes in transmitted light intensity resulting from changes in birefringence that occur during the ligand-induced crystal lattice transitions. Polarization video microscopy was used to record these changes of single crystals at high magnification, and the input data for the software is a greyscale avi video file. In the video, each pixel represents the intensity as a function of time, and the software detects lattice transitions by identifying peaks in the time-derivative of the intensity. The software exports results as figures, csv files, and optional videos.

## System Requirements
Apple computer (OS X 10.15.7)
PC with Linux (CentOS7)
MATLAB 2019b or later (https://www.mathworks.com/products/matlab.html)

## Installation Instructions
1.	Decompress OMAL_PVM_Analyzer_v201216.zip file.
2.  Copy the OPA_v201118 folder into your MATLAB working directory. Alternatively, after launching MATLAB, the folder can be added to your MATLAB path by right-clicking on the folder, and selecting ‘Add to Path’ -> ‘Selected Folders and Subfolders’.
3.	Create a new folder in a desired location (e.g., ~/Desktop/) and copy the .avi file you wish to analyze into it. A sample .avi file (‘tutorial_sample_data.avi’) of the adenine riboswitch crystal solid-solid phase transition has been provided.

## For more information
Included in the compressed file is a tutorial (OPA_v201118_tutorial.docx)describing how to use the software.


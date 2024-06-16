# LOTUS Reader
The LOTUS Reader is a GUI primarily built to read and compile raw Empatica EmbracePlus data over user-defined periods of time. Fragmented 'chunks' of raw timeseries data output by Empatica (i.e., EDA, BVP, systolic peaks, temperature, accelerometer, and event tags) can be selectively reconstituted as continuous timeseries for further processing.

# Installation
1. Install Matlab 2023b or later (a compiled version is available for users without Matlab)
2. Download and install python version 3.11.x prior to using LOTUS (https://www.python.org/downloads/)
3. Install the avro python library as recommended by Empatica using 'pip install avro'
4. Other python libraries (i.e., json, csv, and os) are also required but should be installed with python by default

# To Use LOTUS Reader
1. Start Matlab
2. Add the folder containing LOTUS_reader to the Matlab including subfolders
3. Type "LOTUS_reader" in the Matlab command prompt and press enter
4. Check the instructions PDF for GUI workflow
5. Please send feedback and suggestions to: jack.fogarty@nie.edu.sg

# Compiled version of LOTUS
It is possible to use LOTUS without Matlab but running a compiled version of the app. A compiled version of LOTUS Reader can be made available to users upon request to: jack.fogarty@nie.edu.sg

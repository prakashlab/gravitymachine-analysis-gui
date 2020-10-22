# Squid Analysis GUI 

## Introduction
This is a custom GUI-based data analysis tool for visualizing and analyzing tracking microscopy datasets. This current repo is specifically tuned for tracking microscopy using Squid and is based on earlier such repo for Scale-free vertical Tracking Microscopy aka Gravity machine [D Krishnamurthy et. al : Scale-free Vertical Tracking Microscopy](https://www.nature.com/articles/s41592-020-0924-7). 

The program has a few run-time dependencies which can be installed by following *Installation.md*.

To launch open a terminal, activate the appropriate virtual environment (conda activate ...). After this type:
	
	python DataAnalyser.py

## Basic usage

### Opening a dataset
To open a new dataset, hit *'Ctrl + O'* or click *File > Open*. Then first choose the folder containing the data (.csv track file + folder containing images). In the next dialog, choose the .csv track file you wish to open.

### Changing track parameters
To change track parameters such as Pixel size, chamber dimensions etc., navigate to *Edit > Track* parameters or hit *'Ctrl + T'*. 

### Changing Video Playback speed
To change the playback speed of the video, navigate to *Video > Video Parameters* or hit *'Ctrl + V'*. Use the slider or entry box to enter the playback factor. Playback factor of *'1'* corresponds to real-time playback.


## To cite this tool:
- Krishnamurthy, D., Li, H., Benoit du Rey, F. et al. Scale-free vertical tracking microscopy. Nat Methods (2020). https://www.nature.com/articles/s41592-020-0924-7


## References
- https://gravitymachine.org/

#### Contributors: 
Deepak Krishnamurthy, Francois benoit du Rey and Ethan Li


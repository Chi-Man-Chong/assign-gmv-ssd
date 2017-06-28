# Stop Sign Detection in Google Street View Images Using the Haar Cascade Classifier

Richard Wen  
rwen@ryerson.ca  
June 27, 2017  
Assignment for Geospatial Modelling and Visualization Course  
Instructed by Dr. Wai Yeung Yan  
  
 - [PDF Paper](https://github.com/rrwen/assign-gmv-ssd/blob/master/paper/pdf/index.pdf)
 - [Background Notebook](https://github.com/rrwen/assign-gmv-ssd/blob/master/background/background.ipynb)
 - [Experiment Notebook](https://github.com/rrwen/assign-gmv-ssd/blob/master/experiment/experiment.ipynb)

## Abstract

The success of Google Street View (GSV) has enabled millions of users to visualize particular locations without being present at the locations. This is possible due to the large scale data collection of panorama imagery using vehicular and portable camera systems. The imagery collected by GSV provides a unique source of visual data that can be used to extract valuable and unique geospatial information. The images provide a great opportunity for object detection methods to extract objects of interest from images with geolocation metadata with algorithms such as the popular Haar Cascade Classifier (HCC) proposed by Viola and Jones. This paper used the HCC algorithm to create a stop sign detection model for GSV images as a small experiment in extracting street level geospatial data. The experiment revealed that the HCC algorithm was strongly affected by grayscale image intensities of images, which may change greatly with different distortions, viewing angles, and image qualities. However, the rapid efficiency of the algorithm enables the potential for it to be combined with multiple HCC models to better improve performance. This experiment demonstrated that it was possible to extract unique and valuable geospatial data such as street level stop signs from images with geolocation metadata, which are expensive or impractical to obtain with other standard methods such as Light Detection and Ranging, remote sensing, and manual in-situ surveying.

## Folders

* **background**: Python notes for implementing some code relative to the Viola and Jones Haar Cascade algorithm
* **experiment**: Python notes for running the stop sign detection experiment described in the paper
* **paper**: LaTeX source code for the paper report

## Install

1. Install [Anaconda for Python 3](https://www.continuum.io/downloads)
2. Install [OpenCV 3](http://opencv.org/) via [conda-forge](https://anaconda.org/conda-forge/opencv)
3. Install required Python packages with [pip](https://docs.python.org/3/installing/)

```
conda install -c conda-forge opencv=3.2.0
pip install google_streetview
pip install requests
```

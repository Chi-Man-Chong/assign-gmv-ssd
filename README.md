# Stop Sign Detection in Google Street View Images Using the Haar Cascade Classifier

Richard Wen  
rwen@ryerson.ca  
June 27, 2017  
Assignment for Geospatial Modelling and Visualization Course  
Instructed by Dr. Wai Yeung Yan  
  
 - [PDF Paper](https://github.com/rrwen/assign-gmv-ssd/blob/master/paper/pdf/index.pdf)
 - [Background Notebook](https://github.com/rrwen/assign-gmv-ssd/blob/master/background/background.ipynb)
 - [Experiment Notebook](https://github.com/rrwen/assign-gmv-ssd/blob/master/experiment/experiment.ipynb)

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

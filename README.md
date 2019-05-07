# Plotly based toolbox for fMRI data visualization and exploratory analysis

May this repository be used for the development of the Brainhack Donostia 2019 project named *Plotly based toolbox for fMRI data visualization and exploratory analysis*.

## Key words

fMRI, DWI/aMRI, Data visualization, plotly, python, javascript, CAPs.

## Project abstract

Plotly [1] offers open source graphing library for python and JS that can be used to create captivating interacting plots, which features can be exploited in the visualization and exploratory analysis of fMRI data. In this project, we propose to (a) create a fully explorable 3D plot for maps visualization to be embedded in presentations, inspired by a plotly.py example by Emilia Petrisor [2], and (b) use this 3D plot, combined with a 2D timeseries plot, to deploy a tool for graphical explorative analysis in methods such as Co-Activation Pattern Analysis [3,4]. Co-Activation Pattern Analysis is a widely used method for dynamic Functional Connectivity Analysis, based on the selection of Critical Timepoints (CTP) in a signal. CTP are selected using an arbitrary threshold to individuate the peaks of a Region of Interest timeseries. In order to improve the selection of signal of interest and discard noise, it is possible to discard CTPs based on other measures (e.g. Framewise Displacement). A GUI based exploration of the data might not only be useful for plotting and selecting CTPs, but it could also help investigating the relationship between CTPs and signal of interest. The toolbox will be developed in python and, depending on the time, in JS. The development of the project should take place on Tuesday the 7th.

## Key material

- https://plot.ly/javascript/
- https://plot.ly/python/visualizing-mri-volume-slices/
- Liu, Duyn (2013), https://doi.org/10.1073/pnas.1216856110
- Liu et al. (2018), https://www.sciencedirect.com/science/article/pii/S1053811918300417?via%3Dihub
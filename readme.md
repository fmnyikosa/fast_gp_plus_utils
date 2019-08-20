# Fast Gaussian Process and Utilities

A Gaussian processes framework in MATLAB based on an extensively modified version of [Carl Rasmussen](http://mlg.eng.cam.ac.uk/carl/) and [Hannes Nickisch's](http://hannes.nickisch.org/) [GPML v4.0](http://www.gaussianprocess.org/gpml/code/matlab/doc/). It includes many useful utilities for using GPML for Bayesian Optimization. This code has the following features:

- Gaussian process regression diagnostic tools to test model efficacy; 
- Easy plotting of 1D and 2D data and functions;
- Dummy data generation tools;
- Automatic data standardization utilities;
- Automatic conditioning of ill-fitted data;
- Automatic logging for sequential prediction problems via a formatted cell struct;
- Optional covariance matrix using SVD rather than Cholesky decomposition;
- Integration of Tom Minka's [Lightspeed](https://github.com/tminka/lightspeed) toolbox to increase matrix operation speed.   

## Setup

The root folder contains the file `start.m` which adds the relevent dependencies to the current path. Make sure you run this file before executing anything. 

The root folder also contains demo files for how to use the various features, and the methods have comments about their inputs and outputs.   
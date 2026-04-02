# EOSC454-Inversion-Project-2026


## Background:
Researched Topic:
“How can inverted 1-D soundings from audio-magnetotelluric (AMT) data be used to create pseudo-2D resistivity sections to accurately characterize resistive structures associated with unconformity type uranium deposits, and what are their limitations when compared to a 2-D inverted resistivity model”

## Goals:
The main goals are to produce a forward model and invert the synthetic data to create a pseudo-2D inversion through the stitching/joining of multiple 1-D soundings. Upon creating a trustworthy inversion and stitching workflow, we will then do an inversion using the Cameco data at the McArthur River Mine to identify and characterize possible unconformity type uranium deposits in the region, and comment on the methods possible limitations.

## Data/General Info:
The dataset that will be used throughout this project will be the McArthur River Mine, Saskatchewan data acquired in July-August 2002 by Geosystem Canada Inc. for Cameco Corporation. 

Geological parameters used in the seen code are referenced from Tuncer, 2007. This projects inversion results will also be compared to Tuncer's data. (https://sites.ualberta.ca/~unsworth/theses/Tuncer_EXTECH_MSc_2007_10MB.pdf)


## Installation Instructions:
Everything needed to run the notebooks is in the repository itself (environment file), including the data. The steps you should follow are:

1. Clone the repository then open a terminal, run: 'conda env create -f environment.yml'
2. Run the printed instructions in the terminal
3. Type in 'jupyter notebook'
4. This should take you to an environment! The first document you should run is FDEM_example.ipynb

## Files:
- 304: Geosystem Canada Inc. - Cameco McArthur River Mine line 304 Dataset
- FDEM_example.ipynb: Main Forward Modelling Notebook
- Geological_Figures.png: Figures obtained from Tuncer, 2017 used for property definitions
- environment.yml: Environment YAML file with all libraries needed to run main notebook
- inversion_1d.py: Offical SimPEG pyhton script with minor change for functionality of NSEM (PointNatural Source --> Impedance in Sources)
- mt.py: Offical SimPEG pyhton script with minor change for functionality of NSEM (PointNatural Source --> Impedance in Sources)

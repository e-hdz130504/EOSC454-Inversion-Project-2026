4# EOSC454-Inversion-Project-2026
EOSC454 Inversion Course Project

Researched Topic:
“How can inverted 1-D soundings from audio-magnetotelluric (AMT) data be used to create pseudo-2D resistivity sections to accurately characterize resistive structures associated with unconformity type uranium deposits, and what are their limitations when compared to a 2-D inverted resistivity model”

The main goals are to produce a forward model and invert the synthetic data to create a pseudo-2D inversion through the stitching/joining of multiple 1-D soundings. Upon creating a trustworthy inversion and stitching workflow, we will then do an inversion
using the Cameco data at the McArthur River Mine to identify and characterize possible unconformity type uranium deposits in the region, and comment on the methods possible limitations.

The dataset that will be used throughout this project will be the McArthur River Mine, Saskatchewan data acquired in July-August 2002 by Geosystem Canada Inc. for Cameco Corporation. 

Geological parameters used in the seen code are referenced from Tuncer, 2007. This projects inversion results will also be compared to Tuncer's data. (https://sites.ualberta.ca/~unsworth/theses/Tuncer_EXTECH_MSc_2007_10MB.pdf)

Everything needed to run the notebooks is in the repository itself (environment file), including the data --> Clone the repository then open a terminal, run: 'conda env create -f environment.yml', run the printed instructions in the terminal, then type in 'jupyter notebook'. This should take you to an environment. The first document you should run is FDEM_example.ipynb.

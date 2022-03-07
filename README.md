# 2cRD-wavelength-selection
This repository contains supplementary simulation code for the publication:

__Coarsening and wavelength selection far from equilibrium:
a unifying framework based on singular perturbation theory__

by Henrik Weyer, Fridtjof Brauns, and Erwin Frey.

## Comsol simulations
Large-scale simulations of pattern dynamics are performed in Comsol. The files do not contain simulation results but have to be evaluated first using Comsol Version 5.6.
Make sure to adopt the random seeds when necessary.

Data is exported in a txt file. Python scripts are provided to convert these txt files to hdf5 (found in the same folder). Adopt names where necessary.

## Mathematica notebooks
The Mathematica notebooks are independent and all contain a section _Setup_ at the beginning which has to be evaluated first.
Those notebooks used to evaluate the Comsol simulations import the hdf5 files, which have to be saved in the same directory as the notebooks.

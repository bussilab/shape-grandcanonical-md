# Molecular Dynamics simulations of SHAPE experiments with grand-canonical reweighting 

## Introduction

In this repository you can find code (Jupyter notebooks) and public data associated to [this manuscript](https://arxiv.org/abs/2209.12640).

## Requirements

The following packages are required to run the notebook:

* barnaba 
* mdtraj 1.9.7
* multiprocess 
* pandas 
* pickle
* python 3.9.12
* scikit-learn 
* seaborn 

If you manage your dependencies with conda you can use the [yml file](https://github.com/bussilab/shape-grandcanonical-md/blob/main/shapemd.yml) in the repository.

You can run 

`conda env create -f environment.yml`

to create the conda environment and then 

`conda activate shapemd` 

to activate it.

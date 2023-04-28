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

## Notebooks

In the [notebooks](https://github.com/bussilab/shape-grandcanonical-md/tree/main/notebooks) folder you can find Jupyter notebooks that can be run to reproduce most parts of the analyses carried out in the paper.
Following is a summary of the notebooks and their usage:
- `compute_bindings.ipynb`: compute a tensor of binding frequencies from trajectories with different numbers of reagent copies;
- `gc_reweight.ipynb`: compute the maximum-likelihood partition functions of buffer and binding regions, estimate the chemical potential as a function of the number of particles in the buffer region and compute grand-canonical averages.

## Example Data

In the [data/example_data](https://github.com/bussilab/shape-grandcanonical-md/tree/main/data) folder you can find example data. Example data consist of:
- trajectories (`.xtc` files): a subsampling made with a stride of 250 frames of the original trajectories available for download on [Zenodo](https://zenodo.org/record/7139541#.ZEvzCi1Bzq0)

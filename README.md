[![DOI](https://zenodo.org/badge/253060700.svg)](https://zenodo.org/badge/latestdoi/253060700) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/babakkhavari/Clustering)

# Clustering
Script from: **Population cluster data to assess the urban-rural split and electrification in Sub-Saharan Africa** by Babak Khavari, Alexandros Korkovelos, Andeas Sahlberg, Mark Howells and Francesco Fuso Nerini. Can be used to generate the clusters used in for the Global Electrification Platofrm.

## Content
This repository contains:
* An environment .yml file needed for generating a fully functioning python 3.7 environment necessary for the clustering algorithm.
* The clustering code and related functions. These files also contain necessary steps in order to reproduce results.
* An example case for Benin.

## Installing and running the clustering notebook

**Requirements**

The clustering module (as well as all supporting scripts in this repo) have been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

**Install the clustering repository from GitHub**

After installing Anaconda you can download the repository directly or clone it to your designated local directory using:

```
> conda install git
> git clone https://github.com/global-electrification-platform/Clustering.git
```
Once installed, open anaconda prompt and move to your local "clustering" directory using:
```
> cd ..\Clustering
```

In order to be able to run the clustering tool (main.ipynb and funcs.ipynb) you have to install all necessary packages. "full_project.yml" contains all of these and can be easily set up by creating a new virtual environment using:

```
conda env create --name clustering --file full_project.yml
```

This might take some time. When complete, activate the virtual environment using:

```
conda activate clustering
```

With the environment activated, you can now move to the clustering directory and start a "jupyter notebook" session by simply typing:

```
..\Clustering> jupyter notebook 
```
## Changelog
**5-April-2020**: Original code base published

## Resources
Journal article can be found here: https://www.nature.com/articles/s41597-021-00897-9

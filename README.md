# Water Profiles Project

This repository contains the dataset for the article A priori physical information to aid generalization capabilities of Neural Networks for hydraulic modeling.

## Overview

A set of water profiles were generated by uniformly varying $s$, $b$, $n$, $z_d$, and $Q$ within a specified range, solving equation B.1 using a Finite-Difference scheme. The profiles are sampled with a fixed spatial discretization of $\Delta x$ set to 10 meters, covering a total length of 5000 m resulting in profiles of $N=501$ points.

## Dataset

The dataset used for this project is hosted on OneDrive in the folder named `Water-profiles`. You can access and download the dataset using the following link:

- [Water-profiles Dataset]([https://uniroma3-my.sharepoint.com/:f:/g/personal/gguglielmo_os_uniroma3_it/Eqndpu8m0u1OmVrayBkE7f8BIopG5ma6Uwjr5M3GluLDcQ?e=cK4tHb](https://uniroma3-my.sharepoint.com/:f:/g/personal/gguglielmo_os_uniroma3_it/EnStSAO4qdxJk-DH4xVfT6EBqU_sKS0jc3EzBLfAZx4Dcg?e=2tZmOc)

### Download Instructions

You can manually download the dataset by visiting the link above and clicking on the download button. You will find the file dataset.npz. This file contains the dataset split into training, validation, and test sets. To load the dataset in your Python script, utilize the code provided in Load.py, where you can also discern the structure of the file.

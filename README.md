# Title: Laser Reprogramming Magnetic Anisotropy in Soft Composites for Reconfigurable 3D Shaping
'''https://www.nature.com/articles/s41467-020-20229-6'''
Authors: Heng Deng, Kianoosh Sattari, Yunchao Xie, Ping Liao, Zheng Yan, Jian Lin
Year: 2020
Journal: Nature Communications

## Overview

The Finite Element Analysis (FEA) simulations in this repository are conducted using the Abaqus software. This repository contains the custom subroutine and other relevant files required for the simulations.

The folders in this repository are related to different experiments corresponding to the figures simulated in the published article.


Folders are related to different experiments related to the figures simulated in the published article. 

## File Formats
 .inp files: These files contain the geometry information, the elements, nodes, and their connections.

 .for files: These are UEL subroutines defined in Fortran. The original files are created in reference to the following publications:
        Nature 558, 274 (2018)
        Journal of the Mechanics and Physics of Solids 124, 244 (2019)
These original files have been modified by Kianoosh Sattari.

Using the .inp and .for files, one needs to use the ABAQUS framework to run the simulations.

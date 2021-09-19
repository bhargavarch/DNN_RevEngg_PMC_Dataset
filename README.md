# DNN_RevEngg_PMC_Dataset

This repository contains the hardware performance monitoring counters' traces of popular DNN architectures.
The traces are collected with the use of a popular library (PAPI - https://icl.utk.edu/papi/). We have used these traces to arrive at several results and conclusion in our paper titled "Inferring DNN layer-types through a hardware performance counters based side channel attack."

Please feel free to use this dataset for experimentation and exploration of DNN workloads.
You can access the full paper at the following link:
https://doi.org/10.1145/3486001.3486224 (to be available soon)

The repository contains Jupyter Notebooks, please go through them to understand how to access the dataset.
The "/data" directory contains all the traces in various formats.

If you use this dataset in your research, please cite our paper: 

Dandpati Kumar Bhargav Achary, R Sai Chandra Teja, Sparsh Mittal, Biswabandan Panda, C Krishna Mohan (2021)  Reverse Engineering Layer-profile of Deep Neural Networks using Hardware Performance Counters In: First International Conference on AI-ML-Systems (AIMLSystems '21)  Bengaluru, India:  ACM

@inproceedings {ref142,
title            = "Inferring DNN layer-types through a Hardware Performance Counters based Side Channel Attack",
year             = "2021",
author           = "Dandpati Kumar Bhargav Achary and R Sai Chandra Teja and Sparsh Mittal and Biswabandan Panda and C Krishna Mohan",
booktitle        = " First International Conference on AI-ML-Systems (AIMLSystems)", 
address          = "Bengaluru, India",
publisher        = "ACM",
}


# Deep Learning for Healthcare (CS 598) Course Project

University of Illinois Urbana Champaign

Spring 2022

Brayden Turner & Joshua Smith


## Background
This paper is a reproduction and analysis of the model presented in the paper [INPREM: An Interpretable and Trustworthy Predictive Model for Healthcare](https://dl.acm.org/doi/10.1145/3394486.3403087) from 2020 by Xianli Zhang, Buyue Qian, Shilei Cao, Yang Li, Hang Chen, Yefeng Zheng, and Ian Davidson.

## Running The Code
All the code is contained in a Jupyter notebook [CourseProject.ipynb](https://github.com/braydenturner/DL4H_CourseProject/blob/main/CourseProject.ipynb). 

At the very top is a cell to import some of the modules we used (Sparsemax, numpy, etc.). 

The notebook contains several sections guiding the user through setup, data import and load, training, and model evaluation.


### Flags 

There are two flags that can be used to control operation of the notebook:

`use_demo` specifies whether or not the demo data should be used. Use this setting if you do not have the MIMIC-III dataset stored locally

`print_metrics` specifies whether or not metrics should be printed. Metrics include CPU utilization, RAM utilization, and GPU VRAM utilization.

## Results and Presentation

A presentation of our findings is available on [YouTube](https://youtu.be/8teJ8AcxOyM). The final report is in the [repo](https://github.com/braydenturner/DL4H_CourseProject/blob/main/CS598_DL4H_Course_Project.pdf).

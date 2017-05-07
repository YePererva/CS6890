# AI Supported Maximum PowerPoint Tracking in Microbial Fuel Cell
Final Project in CS6980: Advanced Intelligent System in Clean Energy
Spring 2017

# Abstract
Project addresses challenge of extracting maximum power from microbial fuel cells (MFCs). AI-based approach, that involves use of Convolutional Neural Network (CNN), was developed and compared with standard technique called “Disturb & Observe” (D&O).

# Introduction
Microbial Fuel Cell is an Bio-Electro-Chemical device that utilize exo-electrogenic abilities of certain bacteria strains in order to:
- Produce the electricity in external circuit
- Simultaneous removal of organics / pollutants

![alt text](https://github.com/Pererva/CS6890/blob/master/images/MFC_Classic.png)

# Problem Description
Power generation by MFCs isn’t constant and depends on wide range of operating conditions. Maximum Power Point Tracking (MPPT) is general name of techniques used for finding and keeping conditions where MFC generates maximum of possible power. Most approaches suggest to vary the applied resistance and measure voltage drop and gained current.
Project tries to develop system that would be able to predict the optimal load in next time moment depending on operating condition at current moment.

# Materials and methods

## Input Data Modelling
Input data were created as model of MFC operation with assumptions:
- MFC works in batch mode
- Voltage over time generation is proportional to microbial growth kinetics
- Voltage drops as function of applied resistance is based on semi-saturation equilibrium
Model simulates data that can be collected with method of fixed resistors or digital potentiometer.

Data was saved as csv-file and consisted of 4 fields:
- Operation time
- Applied resistance
- Achieved voltage
- Generated Power

Several simulations were created with varied voltage noise levels

## Modeled data

Built models are represented as 3D-surfaces were gained power is represented as function of two variables: time and applied resistance.

## Model treatment


# Summary

# Software used:
OS: Windows 10 [x64]
Language: Python 3.6.1
Packages used:
- Matplotlib 2 - visualisation and plotting
- Keras - neural network implementation (with TensorFlow and NumPy as dependencies)
- Jupyter - for visualisation/programming in browser 
If  you have problem with installing packages, find and binaries for Python in Windows at http://www.lfd.uci.edu/~gohlke/pythonlibs/
Find instructions for packages installing via pip at https://packaging.python.org/installing/

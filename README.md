# MEI-Reconstruction
This repository contains the code used in my dissertation [*Most Exciting Images in a CNN reconstruction of the mouse brain*](dissertation.pdf) requested by the BCs of Mathematical and Computing Sciences for Artificial Intelligence (BAI) at Bocconi University, Milan.   


# Abstract
This thesis explores the optimization of images as best stimuli for neurons in the visual cortex of a mouse. I will present the structure of the optimization algorithm used to develop these Most Exciting Images (MEI) and implement it in a control environment to verify its behavior before applying it to the main model.   
The main model used to simulate and predict neuron activation is a Digital Twin with a CNN as its core architecture and trained on the comprehensive MICrONS dataset.    
I will explain what challenges I encountered in both the control environment and the main model, what solutions I adopted and compare their effectiveness. Finally I'll expose my findings along with a sample of the MEIs developed and my considerations of the current way to model neuron activation for simple cells in V1 based on them.


# Structure
- [`Control Environment`](Control_Environment.ipynb); contains code relative to challenges, solutions and results encountered in the control environment and used as an initial validation of the results.
- [`Main Model`](Main_Model.ipynb); contains the code and results relative to the control environment used for an initial validation of the results


# Overview
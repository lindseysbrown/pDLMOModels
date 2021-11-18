# pDLMOModels
Code for models used to generate pDLMO predictions from actigraphy data.

This repository contains the code to train and run the models used to predict DLMO in McHill et al.

The model takes as input data standardized and averages into 30 minute bins for a 24 h period of recorded light and activity counts.  Walking through the cells in this notebook trains the model and returns predicted DLMO values based on a classification approach using a two layer neural network with dropout.

Full details of the models can be found in Brown et al., J. Pineal Research, 2021.  Contact Andrew McHill for inquiries on data accessibility.  

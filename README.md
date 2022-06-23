# CREIME – A Convolutional Recurrent model for Earthquake dentification and Magnitude Estimation
This is a demonstration for implementing the CREIME model (https://www.essoar.org/doi/10.1002/essoar.10511140.1) for identifying earthquakes, picking P-arrival time and estimating earthquake magnitudes from 5.12 second windows (sampled at a frequency of 100Hz) containing between 1-2 seconds of signal precededed by pre-signal noise.

# Requirements
```
Python 3.8
Tensorflow 2.8
```

# Using the CREIME Model
```
The model can downloaded from this repository as CREIME_Model.h5 
The code snippets needed to use the model is provided in the Jupyter Notebook CREIME_Model.ipynb
```

# Citation
If you use the model, please use the following bibtex entry for citation:
```
@article{10.1002/essoar.10511140.1,
author = {Chakraborty, Megha and Fenner, Darius and Li, Wei and Faber, Johannes and Zhou, Kai and Rümpker, Georg and Stöcker, Horst and Srivastava, Nishtha},
title = {CREIME -- A Convolutional Recurrent model for Earthquake Identification and Magnitude Estimation},
journal = {Earth and Space Science Open Archive},
pages = {49},
year = {2022},
DOI = {10.1002/essoar.10511140.1},
url = {https://doi.org/10.1002/essoar.10511140.1}
}
```

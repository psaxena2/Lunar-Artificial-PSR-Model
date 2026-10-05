# Lunar Artificial PSR Thermal Model
This repository contains the 1D thermal models and solar illumination functions used to evaluate the thermal stability of artificially created Permanently Shadowed Regions (PSRs) at the Lunar South Pole. It calculates surface and subsurface temperature profiles as a function of time for small-scale excavations. While this specific notebook includes annotations for evaluating the cold-trapping of Volatile Organic Compounds (VOCs), the underlying temperature calculator can be extracted and utilized for any general scientific or operational purpose.

### Interactive Code
You can run this model interactively in your browser without installing any software by clicking the Binder badge below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/psaxena2/Lunar-Artificial-PSR-Model/main?filepath=Lunar_Thermal_Model.ipynb)

### Dependencies
* numpy
* matplotlib
* [heat1d](https://github.com/phayne/heat1d) (Hayne et al., 2017)

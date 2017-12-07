# pyGIMLi @ AGU17

Poster: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1095621.svg)](https://doi.org/10.5281/zenodo.1095621)
Live-Demo:

## Abstract

Many tasks in applied geosciences cannot be solved by a single measurement method and require the integration of geophysical, geotechnical and hydrological methods. In the emerging field of hydrogeophysics, researchers strive to gain quantitative information on process-relevant subsurface parameters by means of multi-physical models, which simulate the dynamic process of interest as well as its geophysical response. However, such endeavors are associated with considerable technical challenges, since they require coupling of different numerical models. This represents an obstacle for many practitioners and students. Even technically versatile users tend to build individually tailored solutions by coupling different (and potentially proprietary) forward simulators at the cost of scientific reproducibility.
We argue that the reproducibility of studies in computational hydrogeophysics, and therefore the advancement of the field itself, requires versatile open-source software. To this end, we present pyGIMLi - a flexible and computationally efficient framework for modeling and inversion in geophysics. The object-oriented library provides management for structured and unstructured meshes in 2D and 3D, finite-element and finite-volume solvers, various geophysical forward operators, as well as Gauss-Newton based frameworks for constrained, joint and fully-coupled inversions with flexible regularization.

In a step-by-step demonstration, it is shown how the hydrogeophysical response of a saline tracer migration can be simulated. Tracer concentration data from boreholes and measured voltages at the surface are subsequently used to estimate the hydraulic conductivity distribution of the aquifer within a single reproducible Python script.


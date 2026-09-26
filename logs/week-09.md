# Week 9

**Dates:** 07-20 to 07-24

## Goals
- Investigate the effect of taper profile on waveguide transmission.
- Validate the EME implementation across a broader wavelength range.
- Begin exploring machine-learning methods for predicting waveguide modal properties.


## Approach and Implementation
- Compared linear, quadratic, and exponential taper profiles using the 200 μm waveguide geometry.
- Calculated transmission and insertion loss for each profile using the existing FEM eigenmode database and EME cascade.
- Examined the wavelength dependence of the tapered-waveguide response over the 1500-1600 nm range.
- Began organizing FEM simulation data into a structured dataset containing wavelength, waveguide width, waveguide height, and effective-index values for the fundamental modes.
- Investigated machine-learning models as surrogate methods for predicting effective index without repeatedly solving the finite-element eigenvalue problem.


## Results
The comparison between taper profiles demonstrated that the longitudinal distribution of the waveguide width affects the calculated insertion loss even when the input and output dimensions remain fixed. The EME model therefore provides a practical method for studying different taper geometries without requiring a new full-wave simulation for every design. In parallel, the FEM-generated model data were organized for machine-learning analysis, establishing the dataset and workflow needed to evaluate surrogate models for effective-index prediction.


## Notes



# Week 10

**Dates:** 07-27 to 07-31

## Goals
- Develop a machine-learning surrogate model for waveguide effective-index prediction.
- Evaluate the accuracy of different regression approaches.
- Continue documenting the EME and FEM results for the research manuscript.


## Approach and Implementation
- Generated and organized a large FEM dataset by varying wavelength, waveguide width, and waveguide height for silicon nitride waveguides with a silicon dioxide cladding.
- Used the calculated fundamental TE and TM effective indices as the target modal properties for machine-learning models.
- Compared linear regression, fully connected neural-network models, and support-vector regression for effective-index prediction.
- Continued revising the manuscripts to document the FEM mode-solving procedure, EME formulation, taper approximation, cosine correction, broadband validation, and machine learning methodology.


## Results
The initial machine-learning results showed that nonlinear models were substantially more accurate than the linear-regression baseline for predicting effective index. The fully connected neural-network and support-vector regression approaches achieved very low prediction errors, demonstrating that the FEM-generated dataset can be used to construct accurate surrogate models for waveguide modal properties. The results also indicated that effective-index prediction is more straightforward than directly predicting chromatic dispersion, since dispersion depends on wavelength derivatives and is therefore more sensitive to small prediction errors. The EME and machine-learning results were implemented into the Machine Learning Opportunities section of the manuscript.



## Notes



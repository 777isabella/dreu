# Week 8

**Dates:** 07-13 to 07-17

## Goals
- Improve the tapered waveguide EME model and quantify the effect of the geometric correction.
- Extend the analysis beyond the original 50 μm linear taper.
- Investigate how taper length and shape affect transmission efficiency. 


## Approach and Implementation
- Applied the cosine-based geometric correction to the EME transmission results and evaluated its effect at 1500nm, and 1600 nm.
- Extended the taper model from the original 50 μm geometry to a 200 μm taper while maintaining the same 3 μm to 1 μm waveguide-width transition.
- Developed MATLAB implementations for different taper profiles, including linear, quadratic, and exponential width transitions.
- Reused the previously calculated FEM eigenmodes and remapped their longitudinal positions to the different taper profiles to avoid unnecessarily repeating the mode calculations.


## Results
The cosine correction reduced the transmission discrepancy associated with the piecewise-rectangular approximation and provided a more consistent comparison with the full-wave results. The EME framework was successfully extended to a 200 μm taper and multiple taper profiles. Initial results showed that the taper profile influences the prediction insertion loss, with the exponential profile producing lower estimated loss than the quadratic and linear profiles for the simulated geometry. These results provided a basis for further investigating how taper geometry can be optimized using the EME model.


## Notes



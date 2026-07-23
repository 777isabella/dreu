# Week 7

**Dates:** 07-06 to 07-10

## Goals
- Validate the tapered waveguide EME model.
- Compare numerical results with full-wave simulations.

## Approach and Implementation
- Implemented the eigenmode expansion algorithm for the tapered waveguide and generated transmission results for a 50 μm taper consisting of 101 slices. Computed transmission, reflection, and loss at wavelengths of 1500 nm, 1550 nm, 1600 nm. Compared the results with independent Tidy3D simulations and investigated the remaining discrepancy.

## Results
The EME model reproduced the wavelength-dependent transmission trend observed in Tidy3D simulations. Although the raw EME method slightly overestimated transmission, analysis showed that the discrepancy originiated from approximating the continuously varying taper with piecewise-constant rectangular slices. A geometric correction based on cosN(θ) was proposed and implemented, substantially improving agreement with the full-wave simulations. The manuscript was updated with representative mode profiles, interpolation methodology, broadband validation, and discussion of the geometric correction.

## Notes



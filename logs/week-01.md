# Week 1

**Dates:** 05-26 to 05-29

## Goals
- Become familiar with the finite-element mode solver and existing FME framework developed and provided by Dr. Simsek.
- Verify the correctness of the dielectric waveguide simulations.
- Begin investigating chromatic dispersion in Si₃N₄ waveguides.

## Approach and Implementation
Reviewed the existing MATLAB code for the finite-element eigenmode solver and investigated how waveguide geometry, refractive indices, and mesh density influence the computed effective indices. Performed simulations for multiple waveguide wdiths and heights while verifying that the solver correctly identified the guided modes. Began generating chromatic dispersion datasets by sweeping wavelength and recording effective indices. Dr. Simsek noted that some of the modes were spurious, so we implemented a PML (perfectly matched layer) to truncate the computation domain so that we can solve the problem faster with fewer unknowns.

## Results
Successfully identified waveguide dimensions that minimized chromatic dispersion. Generated multiple dispersion curves and confirmed expected transitions between normal and anamolous dispersion regimes. These databases became the foundation for subsequent waveguide optimization studies.

## Notes
This week was full of new information for me to learn and accustom myself to, but Dr. Simsek was so understanding and so helpful.


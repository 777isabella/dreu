# Week 4

**Dates:** 06-15 to 06-19

## Goals
- Begin development of the tapered waveguide model.
- Adapt the finite-element solver for longituidially varying structures.

## Approach and Implementation
Designed the computatonal framework for representing a atapered wavehuide as a sequence of uniform cross sections. Generated finite-element meshes for multiplr taper widths ehile maintaining identical simulation domains and material properties. Investigated suitable mesh densities for accurately representing the taper.

## Results
Successfully generated cross-sectional meshes for the taper geometry and verified that the computed guided mode evolved smoothly as the waveguide width decreased.

## Notes
The .mat files being produced were so large because I was having the script save the results twice.

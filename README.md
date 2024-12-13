# Analysis of Four Particles in a Periodic Cosine Potential
[Location of this project](https://github.com/dsmic/FourParticlesInAPeriodicPotential)

## Overview
This repository contains the analysis and results of a study on four quantum particles in a one-dimensional periodic cosine potential. The main objective is to investigate the effects of spin configurations and spatial arrangements on the system's total energy.

The study evaluates scenarios such as:
- All particles localized in separate wells.
- Two neighboring particles with opposite spins.
- Two neighboring particles with same spins.
- Three neighboring particles with same spins.

## Key Findings
- **Same-spin neighbors**: Total energy increases due to exchange interaction.
- **Opposite-spin neighbors**: No change in total energy, as the system lacks electron-electron interactions.

## Approach
1. **Potential Setup**:
   - A periodic potential defined as:
     ```
     V(x) = -A * cos(2 * pi * a * x)
     ```

2. **Wavefunctions**:
   - Spatial wavefunctions modeled as localized Gaussians.
   - Spins indexed using `~σ_i` for each basis function.

3. **Energy Calculations**:
   - Total energy calculated by analytically evaluating integrals and numerically minimizing localization width parameters `α_i`.

## Contents
- `four_particle_study.tex`: LaTeX document containing the full study.
- Figures: Plots generated for each configuration.
  - `IMGseparated.pdf`: All particles separated.
  - `IMGopposite_spin_neighbor.pdf`: Two opposite-spin neighbors.
  - `IMGsame_spin_neighbor.pdf`: Two same-spin neighbors.
  - `IMGthree_same_spin.pdf`: Three same-spin neighbors.

## Future Directions
This analysis forms the foundation for exploring more complex systems, such as j-T models, and understanding the role of exchange interactions in realistic physical systems.

---

*This documentation was prepared with the assistance of AI tools.*

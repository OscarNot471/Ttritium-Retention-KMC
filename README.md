# Tritium Retention KMC

Kinetic Monte Carlo simulation of tritium diffusion, trapping and recombination on a simplified tungsten surface.

This repository contains the code and supplementary material developed during my curricular internship in the Degree in Physics at the University of Alicante.

## Model

The tungsten surface is represented by a two-dimensional periodic lattice. Tritium particles can:

- diffuse between neighbouring sites,
- become trapped in defects,
- escape from traps,
- recombine and leave the surface,
- enter the system through an incident particle flux.

The model includes four effective types of defects:

- vacancies,
- dislocations,
- grain boundaries,
- cavities.

The simulations were performed at three temperatures:

- 300 K,
- 700 K,
- 1500 K.

## Repository contents

- `Tritium-Diffusion_KMC.py`: main kinetic Monte Carlo simulation code.
- `animations/`: animations obtained for the simulations at 300 K, 700 K and 1500 K.

## Main parameters

- Lattice size: 200 × 200 sites
- Initial number of tritium particles: 50
- Initial occupation fraction: 0.125%
- Migration energy: 0.25 eV
- Attempt frequency: 1.90 × 10¹³ s⁻¹
- Incident flux: 10²⁴ m⁻² s⁻¹

## Requirements

The code was developed in Python and requires:

- NumPy
- Matplotlib

## Author

Óscar Notario Poveda  
Degree in Physics  
University of Alicante

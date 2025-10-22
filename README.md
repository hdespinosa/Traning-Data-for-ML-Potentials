# Traning-Data-for-ML-Potentials
"Generalizable Machine Learning Potentials for Quantum-Accurate Predictions of Non-Equilibrium Behavior in 2D Materials.” Includes DFT-derived training, validation, and test data for MoSe₂ used to develop and benchmark SNAP and Allegro ML potentials for accurate, transferable modeling of 2D materials.

This repository provides the complete training, validation, and test datasets used in the paper “Generalizable Machine Learning Potentials for Quantum-Accurate Predictions of Non-Equilibrium Behavior in 2D Materials.” The data support the development and benchmarking of two advanced machine learning interatomic potentials (ML-IAPs)—Spectral Neighbor Analysis Potential (SNAP) and Allegro—trained on density functional theory (DFT) calculations for monolayer MoSe₂.

The datasets encompass equilibrium and non-equilibrium atomic configurations, including cohesive energies, elastic constants, stress–strain curves, bond-dissociation landscapes, phase transition energetics, defect formation energies, and finite-temperature ab initio molecular dynamics snapshots. These data were curated to capture a wide diversity of atomic environments, enabling the trained potentials to predict complex phenomena such as defect evolution, surface reconstructions, inversion domain formation, and fracture toughness with near-DFT accuracy.

By providing this repository, we aim to promote reproducibility and accelerate the design of generalizable ML-based force fields for 2D materials and beyond. The included scripts and metadata specify the structure, energy, and force data used for parameterization and benchmarking of SNAP and Allegro within the LAMMPS and Allegro frameworks.

Key results from the study demonstrate that Allegro achieves DFT-level accuracy at dramatically reduced computational cost, while both ML-IAPs outperform traditional empirical potentials (e.g., Tersoff) under large deformations and defect-rich conditions. The datasets thus serve as a foundation for training new ML potentials capable of modeling non-equilibrium mechanical behavior, enabling large-scale simulations of stress-driven transformations, defect nucleation, and fracture in low-dimensional materials.

Contents:

DFT-derived training, validation, and test data

Metadata and configuration files

Example scripts for model training and evaluation

Benchmarking data for SNAP, Allegro, and Tersoff potentials

# Thomson Problem - Coulomb Charges on a Sphere (Monte Carlo Method)

This repository contains the Jupyter Notebook for solving the Thomson Problem using **Monte Carlo methods**, where Coulomb charges are placed on a unit sphere and optimized through an annealing procedure.

## Table of Contents

- Introduction
- File
- Usage
- References

## Introduction

In this study, we solve the **Thomson Problem** using **Monte Carlo methods**. The objective is to find the optimal configuration of N Coulomb charges on the surface of a unit sphere. An annealing procedure is applied to minimize the total energy by exploring the configuration space. The notebook includes the calculation of the optimal charge positions, the energy of the system, and the radial distribution function.

Additionally, the repository contains a CSV file `NUthom.csv`, which contains data from the following studies:

- Wales, D. J., & Ulker, S. (2006). Structure and dynamics of spherical crystals characterized for the Thomson problem. *Physical Review B, 74*(21), 212101.
- Wales, D. J., McKay, H., & Altschuler, E. L. (2009). Defect motifs for spherical topologies. *Physical Review B, 79*(22), 224115.

## File

- Jupyter notebook: `Thomson_Problem_MonteCarlo.ipynb`
- Data file: `NUthom.csv` (contains data from the referenced studies)

## Usage

1. Clone the repository.
2. Open the `Thomson_Problem_MonteCarlo.ipynb` file using Jupyter Notebook.
3. Follow the instructions within the notebook to perform the Monte Carlo annealing procedure and visualize the optimal charge configuration.
4. Review the optimal configuration, energy, and radial distribution function.
5. The `NUthom.csv` file contains supplementary data that can be analyzed or used for comparison with the results.

## References

- Wales, D. J., & Ulker, S. (2006). Structure and dynamics of spherical crystals characterized for the Thomson problem. *Physical Review B, 74*(21), 212101.
- Wales, D. J., McKay, H., & Altschuler, E. L. (2009). Defect motifs for spherical topologies. *Physical Review B, 79*(22), 224115.

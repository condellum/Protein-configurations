# Protein-configurations

**Project for the Statistical Biophysics course (Master in Physics of Complex Systems at IFISC-UIB):  
An Efficient Algorithm for Exploring Protein Configurations with Two and Three Polarities**

Protein folding is a fundamental process in biology that determines the three-dimensional structure of proteins, which is essential for their function. Understanding the mechanisms underlying protein folding has been a long-standing goal in biophysics, yet no final solution has been reached. However, several models have been developed to approximate the process. One of the simplest is the Hydrophobic-Polar (HP) model, which classifies amino acids into two categories: hydrophobic (H) and polar (P). This classification simplifies the study of protein folding by focusing on the tendency of hydrophobic residues to cluster away from the aqueous environment.

In this project, we explore the classical HP model along with an extended version that includes three different polarities. Our goal is to determine the optimal folding configuration—without tying ourselves to a specific protein sequence—in order to approximate structures frequently observed in real proteins. We implement our approach on a 6x6 two-dimensional grid using Python and NumPy for efficient matrix operations. The algorithm computes the energy of all possible configurations for a given polarity sequence and iterates over many random polarity sequences to identify the lowest-energy states.
## Repository Structure

```plaintext
Protein-configurations/
├── data/
│   └── grid_paths.txt         # List of all possible foldings in a 6x6 grid
├── notebooks/
│   └── main_notebook_biophysics_project.ipynb  # Code for obtaining the results
└── results/
    └── report_biofisica.pdf     # Detailed explanation of methodology and results

    

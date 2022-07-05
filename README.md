# LoCoMock

The LoCoMock score is useful in docking simulation for membrane protein.


It use membrane position and logP to validate docking poses.
  
# DEMO  
![demonstration](https://user-images.githubusercontent.com/3397013/177257670-1094ffc2-cceb-4be6-a1fb-795fd3af8f34.png)


# Features

 
# Requirement (validated version)
  
- Jupyter_Dock (v0.2.5)
- Python 3.x (3.7.10)
 - matplotlib                3.4.3
 - numpy                     1.19.1
 - py3dmol                   0.9.2
 - vina                      1.2.2
 - openbabel                 3.1.1
 - rdkit                     2021.03.5
 
# Installation
Place LoCoMock_std.ipynb in the directory "Jupyter_Dock".

 
# Usage
Launch LoCoMock_std.ipynb.


Place PDB files for protein (protein.pdb) and ligand (ligand.pdb) in the ./LoCoMock/{str_id} .

 
# Note
Please cite this paper.


Rikuri Morita, Yasuteru Shigeta, Ryuhei Harada. LogP-corrected Membrane Docking for Ligand-Protein Complexes. Submitted (2022)DOI:[https://doi.org/]

 
# Author
- Rikuri Morita*, Yasuteru Shigeta, Ryuhei Harada*.
- Center for Computational Sciences, University of Tsukuba
- morita@ccs.tsukuba.ac.jp
 
# License
LoCoMock is a modified extension of Jupyter_Dock[https://github.com/AngelRuizMoreno/Jupyter_Dock].


LoCoMock is under MIT license.

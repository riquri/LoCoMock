# LoCoMock

The LoCoMock score is useful in docking simulation for membrane protein.


It use membrane position and logP to validate docking poses.
  
# DEMO  
![github_demo](https://user-images.githubusercontent.com/3397013/225182550-fb2f4b51-b209-484b-8592-6374a0fbaf1c.png)

# Features

 
# Requirement (validated version)
  
- Jupyter_Dock (v0.2.5)
- Python 3.x (3.10.9)
 - matplotlib                (3.6.3)
 - numpy                     (1.23.5)
 - py3dmol                   (2.0.1)
 - vina                      (1.2.3)
 - openbabel                 (3.1.1)
 - rdkit                     (2022.09.4)
 
 
# Installation
Install AutoDock, [JupyterDock](https://github.com/AngelRuizMoreno/Jupyter_Dock), and other required packages.
Place LoCoMock_std.ipynb in the directory "Jupyter_Dock".

 
# Usage
Launch LoCoMock_std.ipynb.


Place PDB files for protein (protein.pdb) and ligand (ligand.pdb) in the ./LoCoMock/{str_id} .

 
# Note
Please cite this paper.


Rikuri Morita, Yasuteru Shigeta, Ryuhei Harada. Efficient Screening of Protein-Ligand Complexes in Lipid Bilayers Using LoCoMock Score. (2023) J. Comput. Aided Mol. Des. DOI:[https://doi.org/10.1007/s10822-023-00502-8]

 
# Author
- Rikuri Morita*, Yasuteru Shigeta, Ryuhei Harada*.
- Center for Computational Sciences, University of Tsukuba
- morita@ccs.tsukuba.ac.jp
 
# License
LoCoMock is a modified extension of Jupyter_Dock[https://github.com/AngelRuizMoreno/Jupyter_Dock].

LoCoMock is under MIT license.

# Molecular Dynamics Structures and Data for 2,4-D Adsorption on Biochars Study

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17990327.svg)](https://doi.org/10.5281/zenodo.17990327)

[![arXiv](https://img.shields.io/badge/arXiv-2512.22573-b31b1b.svg)](https://arxiv.org/abs/2512.22573)

Data for the paper titled "*Unravelling 2,4-D – biochar interactions by molecular dynamics: adsorption modes and surface functionalities*" by Rosie Wood, Ondřej Mašek, and Valentina Erastova. ArXiv Preprint DOI: [10.48550/arXiv.2512.22573](https://doi.org/10.48550/arXiv.2512.22573) (2025)


The data is organised as follows:
- Each directory contains data for a specific biochar -- `BC400`, `BC600`, and `BC800`.
- The sub-directories withing biochar directory correspond to given concentrations -- `c1`, `c2`, ... `c8`.
- Within these subdirectories the following files are given:
  - `eq_sys.gro` -- equilibrated biochar + 2,4-D + water system;
  - `system.topol` --  topology file for the given system;
  - `mdout.mdp` and `topol.tpr` -- compiled files for production run.
- We also provide:
  - include topology files (`.itp`) and atom type files (`.atp`) for biochars within biochar directory and for 2,4-D within main directory;
  - `gra_oplsaa.ff` -- an OPLS-AA folder within main directory.
  - These files are linked within the `system.top` of all systems.

The details on constructing and validating biochar models used in this work can be found in: 
- Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Developing realistic molecular models of biochars." Cell Reports Physical Science 5.7 (2024). [doi.org/10.1016/j.xcrp.2024.102037](https://doi.org/10.1016/j.xcrp.2024.102037); and
- downloaded from [github.com/Erastova-group/Biochar_MolecularModels](https://github.com/Erastova-group/Biochar_MolecularModels).


Any questions, please open an issue or email valentina.erastova@ed.ac.uk


------

If you use our models **please cite** our work:
1. Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Unravelling 2,4-D – biochar interactions by molecular dynamics: adsorption modes and surface functionalities." ArXiv Preprint DOI: [10.48550/arXiv.2512.22573](https://doi.org/10.48550/arXiv.2512.22573) (2025).
2. Valentina Erastova. "Erastova-group/24D_biochar: zenodo (v1.1)" Zenodo. [doi.org/10.5281/zenodo.17990328](https://doi.org/10.5281/zenodo.17990328) (2025). 
3. Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Developing realistic molecular models of biochars." Cell Reports Physical Science 5.7 (2024).

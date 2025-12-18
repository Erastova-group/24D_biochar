# 24D_biochar

Data for the paper titled "*Unravelling 2,4-D – biochar interactions by molecular dynamics: adsorption modes and surface functionalities*" by Rosie Wood, Ondřej Mašek, and Valentina Erastova (2025).



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
- Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Developing realistic molecular models of biochars." Cell Reports Physical Science 5.7 (2024). [doi.org/10.1016/j.xcrp.2024.102037](https://doi.org/10.1016/j.xcrp.2024.102037),
- and downloaded from [github.com/Erastova-group/Biochar_MolecularModels](https://github.com/Erastova-group/Biochar_MolecularModels).


Any question, please open an issue or email valentina.erastova@ed.ac.uk


------

If you use our models **please cite** our work:
1. Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Unravelling 2,4-D – biochar interactions by molecular dynamics: adsorption modes and surface functionalities," XXXXXXX (2025).
2.  Rosie Wood, Ondřej Mašek, and Valentina Erastova. "Developing realistic molecular models of biochars." Cell Reports Physical Science 5.7 (2024).

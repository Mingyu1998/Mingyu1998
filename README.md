## Mingyu Qin

DPhil candidate in Biochemistry at the **University of Oxford** (Khalid Group), working in computational biochemistry and membrane biophysics.

I use multiscale molecular dynamics, from all-atom to Martini coarse-grained, to study how antimicrobial agents interact with the bacterial cell envelope. The goal is to understand, and help optimise, candidate antibiotics against Gram-negative bacteria.

[![Email](https://img.shields.io/badge/Email-mingyu.qin%40bioch.ox.ac.uk-002147?style=flat-square)](mailto:mingyu.qin@bioch.ox.ac.uk)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--3507--0430-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-3507-0430)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mingyu%20Qin-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mingyu-qin-708a651b9/)

### Research interests

- **Bacterial membranes.** Structure and dynamics of the Gram-negative outer membrane, LPS, and asymmetric bilayers.
- **Membrane-active antimicrobials.** How polymers, peptides and proteins bind to, insert into and perturb bilayers.
- **Multiscale simulation.** Coarse-grained (Martini 2/3) and all-atom MD, with QM parameterisation where needed.
- **Reproducible workflows.** Scripted system building and analysis pipelines that run on HPC.

### Selected projects

| Project | What it is |
| :-- | :-- |
| [**MDBuddy**](https://github.com/Mingyu1998/MDBuddy) | Command-line tool and agent skill that builds Martini membrane-protein systems for GROMACS from a PDB ID and a membrane spec. Every step is logged with checksums, so a build can be reproduced exactly. |
| [**MD_Prot-Memb**](https://github.com/Mingyu1998/MD_Prot-Memb) | MDAnalysis toolkit for protein–membrane simulations: leaflet assignment (including DBSCAN for curved bilayers), thickness and curvature maps, S<sub>CD</sub> order parameters, and parallel contact analysis. |
| [**MRes_Project_COX-2**](https://github.com/Mingyu1998/MRes_Project_COX-2) | All-atom MD of the COX-2 homodimer, testing how paracetamol, dipyrone metabolites and arachidonic acid occupy the cyclooxygenase and peroxidase sites. Uses Amber, MM/PBSA and Gaussian-derived ligand parameters. |
| [**E.coli_OM**](https://github.com/Mingyu1998/E.coli_OM) | Building and analysing *E. coli* outer-membrane models with LPS: a modified INSANE builder, plus 2D lipid density analysis. |

### Tools

**Simulation:** GROMACS · Amber (pmemd.cuda) · Martini 2.2 / 3 · martinize2 · COBY · INSANE · Gaussian 16  
**Analysis:** Python · MDAnalysis · pytraj / cpptraj · NumPy · SciPy · Matplotlib · Jupyter  
**Computing:** Linux · Bash · HPC clusters · Git

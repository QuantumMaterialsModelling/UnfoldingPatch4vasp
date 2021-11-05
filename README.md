# Unfolding Patch for VASP

This patch allows you to include the latest version of the Unfolding algortihm in your VASP package.

The patch file vasp.6.2.1_U-patch.21.08 (patch version 21.08) has been tested for the VASP version 6.2.1.

The implementation of the Unfolding method as included in the patch package is described in:\\
{\sl Electronic State Unfolding for Plane Waves: Energy Bands, Fermi Surfaces, and Spectral Functions}, D. Dirnberger, G. Kresse, C. Franchini, and M. Reticcioli, {\sl The Journal of Physical Chemistry C} 23, 12921 (2021), \href{https://pubs.acs.org/doi/10.1021/acs.jpcc.1c02318}{DOI:10.1021/acs.jpcc.1c02318}.
This version supports the \href{https://github.com/QuantumMaterialsModelling/bands4vasp}{\textbf{bands4vasp}} external tool for an immediate analysis of unfolding calculations.\\
Core routines were developed for previous VASP versions, as described in:
{\sl Indirect-to-direct gap transition in strained and unstrained Sn$_x$Ge$_{1-x}$ alloys}, C. Eckhardt, K. Hummer, and G. Kresse, Physical Review B 89(16), 165201 (2014), \href{https://doi.org/10.1103/PhysRevB.89.165201}{DOI:10.1103/PhysRevB.89.165201}.

## Getting started

### Installation

1) Downaload the patch file (e.g., the vasp.6.2.1_U-patch.21.08 file) in the root directory of your vasp package.

2) Apply the patch to execute the command:
patch -p0 < vasp.6.2.1_U-patch.21.08
        
### Usage

Please refer to the wiki (pdf) document included here.

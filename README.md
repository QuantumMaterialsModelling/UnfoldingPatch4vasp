# Unfolding Patch for VASP

This patch allows you to include the latest version of the Unfolding algortihm in your VASP package.

The patch file vasp.6.2.1_U-patch.21.08 (patch version 21.08) has been tested for the VASP version 6.2.1.

The implementation of the Unfolding method as included in the patch package is described in\
_Electronic State Unfolding for Plane Waves: Energy Bands, Fermi Surfaces, and Spectral Functions_, D. Dirnberger, G. Kresse, C. Franchini, and M. Reticcioli, _The Journal of Physical Chemistry C_ 23, 12921 (2021), https://pubs.acs.org/doi/10.1021/acs.jpcc.1c02318 .

This version supports the _bands4vasp_ external tool for an immediate analysis of unfolding calculations (see https://github.com/QuantumMaterialsModelling/bands4vasp ).

Core routines were developed for previous VASP versions, as described in:\
_Indirect-to-direct gap transition in strained and unstrained Sn(x)Ge(1-x) alloys_, C. Eckhardt, K. Hummer, and G. Kresse, _Physical Review B_ 89(16), 165201 (2014), https://doi.org/10.1103/PhysRevB.89.165201 .

## Getting started

### Installation

1) Downaload the patch file (e.g., the vasp.6.2.1_U-patch.21.08 file) in the root directory of your vasp package.

2) Apply the patch by executing the command:\
patch -p0 < vasp.6.2.1_U-patch.21.08
        
### Usage

Please refer to the wiki (pdf) document included here.

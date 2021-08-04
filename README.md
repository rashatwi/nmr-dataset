# Overview

This GitHub repository contains the dataset accompanying the following manuscript:
* R. Atwi, Y. Chen, K.S. Han, V. Murugesan, N.N. Rajput. "An automated framework for predicting NMR chemical shifts of liquid solutions". (2021). 

The dataset includes the Nuclear Magnetic Resonance (NMR) tensors and chemical 
shifts computed using our automated computational framework that combines density 
functional theory (DFT) with classical molecular dynamics (MD) simulations as 
implemented in the MISPR high-throughput infrastructure. \
The data corresponds to solvation structures for a magnesium bis(trifluoromethanesulfonyl)imide Mg(TFSI)2 in 
dimethoxyethane (DME) solvent, which is a common electrolyte system for Mg-based 
batteries.

# DFT Benchmarking Study
The benchmarking study includes almost 1,000 DFT calculations. It involves the 
following combinations of functionals, basis sets, and implicit solvation models:

| Functional    | Basis Set | Solvation Model 
| ------------- | ------------- | -------------
| B3LYP  | 6-31+G*  | PCM
| M06-2X | 6-311++G** | SMD
| PBE1PBE  | def2-TZVP
| wB97X | 

# Contact 
If you have any questions, you can reach the author at the following e-mail:
rasha.atwi@stonybrook.edu

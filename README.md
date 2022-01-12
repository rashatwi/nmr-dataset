# Overview

This GitHub repository contains the dataset accompanying the following manuscript:
* R. Atwi, Y. Chen, K.S. Han, V. Murugesan, N.N. Rajput. "An automated framework for predicting NMR chemical shifts of liquid solutions". (2021). 

The dataset includes the Nuclear Magnetic Resonance (NMR) tensors and chemical 
shifts computed using our automated computational framework that combines density 
functional theory (DFT) with classical molecular dynamics (MD) simulations as 
implemented in the MISPR high-throughput infrastructure. 

The lactam data corresponds to different conformers of penam β-lactams in chloroform solvent. The electrolyte data corresponds to solvation structures for: (1) a magnesium bis(trifluoromethanesulfonyl)imide Mg(TFSI)2 in dimethoxyethane (DME) solvent and (2) LiTFSI in DME which are common electrolyte system for Mg- and Li-based 
batteries, respectively. Solvation structures were extracted from MD simulations at 25 °C, 1 atm, and a salt:solvent ratio of 1:18. 

# DFT Benchmarking Study
The benchmarking study on the electrolyte system includes almost 1,000 DFT calculations. It involves
combinations of the following functionals, basis sets, and implicit solvation models:

| Functional    | Basis Set | Solvation Model 
| ------------- | ------------- | -------------
| B3LYP  | 6-31+G*  | PCM
| M06-2X | 6-311++G** | SMD
| PBE1PBE  | def2-TZVP
| wB97X | 

# Contact 
If you have any questions, you can reach the author at the following e-mail:
rasha.atwi@stonybrook.edu

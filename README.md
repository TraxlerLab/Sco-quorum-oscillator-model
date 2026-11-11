# Sco-quorum-oscillator-model
This code contains all the code pertaining to Sridhar et al. (2026), including the mathematical model and code to analyze oscillatory dynamics. 

This repository has three branches. The following is a description of what is in each branch. 

---Main---
Both of these files contain the full mathematical model, and when run, both will simulate spatiotemporal expression of each component of the S. coelicolor QS circuit. "Kymographs_FINAL.m" will generate a kymograph measuring cpkO/N along the radius of a simulated colony in real time, while "EdgePlots_FINAL.m" will plot cpkO/N at the colony edge. 

---Measuring-amplitude-and-periodicity---
This contains the code necessary to measure the amplitude and periodicity of simulated cpkO/N pulses at the colony edge. "run_and_measure.m" is the code, that, when run, measures amplitude and periodicity. "run_qs_sim. " must be in the same folder for it to run properly.

---Sensitivity-analysis---
This branch contains all the necessary files to run a sensitivity analysis on the Sco quorum oscillator model. "Plot_sweeps_filtered.m" is the code that performs the sensitivity analysis, and all other files must be in the same source folder. 

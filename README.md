# Viral Metabolism Rewiring (Kelman et al.)

This repository contains the resources for the rewiring paper, organized into:
	1.	Zipped FASTA files
	2.	Python / notebook code
	3.	CSV files with processed results

## 1. Zipped FASTA files
Zipped FASTA files for the reef metagenomes are provided in the  fastas/  directory, as listed in Supplementary Table 1 of the manuscript.
Each zip archive contains one or more  .fasta  files representing viral or microbial communities from individual reef sites.
See the manuscript Methods section for exact sample IDs and site metadata.

## 2. Python / notebook code
Analysis and modeling code are provided as Jupyter notebooks:
	•	 Rho Model code.ipynb  – reef-scale model linking viral metabolism to microbialization
	•	 Rho stats code.ipynb  – statistical analyses and figure generation
Typical workflow:
conda env create -f environment.yml
conda activate viral-metabolism
jupyter notebook “Rho Model code.ipynb”
jupyter notebook “Rho stats code.ipynb”
(Adjust the environment name or notebook names here if they differ in the repository.)

## 3. CSV result files
Processed data products used in the figures and tables are provided as CSV files:
	•	 Data Level 1 SEED Representative 20250501.csv  – functional annotations
	•	 Degraded_With_Virus_Metabolism.csv 
	•	 Healthy_With_Virus_Metabolism.csv 
	•	 Degraded_With_Virus.csv 
	•	 Healthy_With_Virus.csv 
	•	 Degraded_No_Virus.csv 
	•	 Healthy_No_Virus.csv 

These tables summarize metabolic pathway abundances and treatment or site categories
(e.g., healthy vs degraded, with vs without viruses).

## Citation for this repository:
github.com/hopefulmonstersucla/viral-metabolism (v1.0, code and data for Kelman et al.)

## Preprint
This work is described in detail in the preprint:

Kelman et al. (2025) *Rewiring host metabolism links lytic/temperate viruses to reef microbialization*.  
bioRxiv: https://doi.org/10.1101/2025.09.25.676695v1

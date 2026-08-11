# ATXN2 CRC – reproducibility code

This repository contains R scripts used for the analysis of:
**“An ATXN2-linked stress granule transcript program marks proliferative and CD8-low core in colorectal cancer”**

## Data availability (Zenodo)
All analysis-ready inputs/objects and key output tables are deposited on Zenodo:
DOI: 10.5281/zenodo.21885720

Download the Zenodo files and place them in a local folder of your choice.
The scripts use file paths defined inside each script (PROJECT_ROOT variable) and/or can be adapted.

## Scripts
- `scripts/01_bulk.R`  bulk cohorts primary endpoint + meta-analysis + controls
- `scripts/02_m6A.R`  m6A machinery analyses
- `scripts/03_ImmuneDeconv.R`  immune deconvolution associations
- `scripts/04_scRNA.R`  scRNA pseudobulk ligand screen + CellChat outputs
- `scripts/05_Spatial1.R`  Visium HD spatial analyses
- `scripts/05_Spatial2.R`  CytAssist replication spatial analyses
- `scripts/06_Proteomics.R`  CPTAC proteomic anchoring

## Frozen signatures
All gene lists used are provided in:
- `signatures/signatures_v1.csv`

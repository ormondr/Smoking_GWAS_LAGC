# Smoking_GWAS_LAGC

This repository contains the analysis workflow for the **GWAS meta-analysis of smoking traits** as part of the **Latin American Genomic Consortium (LAGC)**.

**Authors:** [Rafaella Ormond](https://github.com/ormondr) and [José Jaime Martinez-Magaña](https://github.com/martinezjaime)

**Analysis plan and phenotype details:**  
📄 [View the full document here](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

---
## 🌎 Available in different languages:
The scripts are available in **English**, **Spanish**, and **Portuguese**.  
Please select the desired language folder:
- `English/`
- `Espanol/`
- `Portugues/`

## Repository Structure

The scripts are organized into the following steps (inside the selected language folder):

### Quality Control (`00QC`)
- `00arrayqc_preimputation/`: Pre-imputation QC  
- `01arrayqc_postimputation/`: Post-imputation QC

### Data Preparation (`01dataprep/`)
- `00dataprep_qc/`: QC preparation for analysis  
- `01dataprep_gwas/`: Data formatting for GWAS

### GWAS Execution (`02GWAS/`)
Contains scripts for running GWAS using the following software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`


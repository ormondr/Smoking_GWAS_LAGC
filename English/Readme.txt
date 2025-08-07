## Smoking GWAS in LAGC<br>
**Authors:** [Rafaella Ormond](https://github.com/ormondr) and [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---
This repository contains the analysis workflow for the **GWAS meta-analysis of smoking traits** as part of the **Latin American Genomic Consortium (LAGC) [LINK](https://www.latinamericangenomicsconsortium.org/pt)**

**Analysis plan and phenotype details:**  
📄 [View the full document here](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

### Repository Structure

### Quality Control (`00QC/`)
- `00arrayqc_preimputation/`: Pre-imputation QC  
- `01arrayqc_postimputation/`: Post-imputation QC

### Data Preparation (`01PC/`)
- `00PCAir/`: Principal Components Calculation for the analysis
  
### Data Preparation (`02dataprep/`)
- `00dataprep_gwas/`: Data formatting for GWAS

### GWAS Execution (`03GWAS/`)
Contains scripts for running GWAS using the following software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`

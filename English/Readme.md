## Smoking GWAS in LAGC<br>
**Authors:** [Rafaella Ormond](https://github.com/ormondr) and [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---

For more information about the phenotypes, please refer to the following analysis plan:

📄 [View analysis plan here] (https://docs.google.com/document/d/1DNIL7f9_f1zhSIBOIzSpxEV-9lUjsZxbvsxgYS3t7x8/edit?usp=sharing)

---

### Repository Structure

### Quality Control (`00QC/`)
- `00arrayqc_preimputation`: Pre-imputation QC  
- `01arrayqc_postimputation`: Post-imputation QC

### Data Preparation (`01PC/`)
- `00PCAir`: Principal Components Calculation for the analysis

### GWAS Execution (`02GWAS/`)
Contains scripts for running GWAS using the following software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`

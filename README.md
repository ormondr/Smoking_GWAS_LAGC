# Smoking GWAS LAGC /  GWAS Consumo de Tabaco en LAGC/ GWAS Consumo de Tabaco no LAGC

***English:*** This repository contains the analysis workflow for the **GWAS meta-analysis of smoking traits** as part of the **Latin American Genomic Consortium (LAGC)[LINK]()**

***Español:*** Este repositorio contiene el flujo de trabajo para el **Meta-análisis de GWAS del consumo de Tabaco** como parte del **Latin American Genomic Consoritium (LAGC) [LINK]()**

***Português:*** Este repositório contem o fluxo de trabaho para a **Meta-análise de GWAS de consumo de Tabaco** como parte do **Latin American Genomic Consoritium (LAGC) [LINK]()**

**Authors:** [Rafaella Ormond](https://github.com/ormondr) and [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

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

### Data Preparation (`01PC/`)
- `00PCAir/`: Principal Components Calculation for the analysis
  
### Data Preparation (`02dataprep/`)
- `00dataprep_gwas/`: Data formatting for GWAS

### GWAS Execution (`03GWAS/`)
Contains scripts for running GWAS using the following software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`


# 🧬 Smoking_GWAS_LAGC

This repository contains the analysis workflow for the **GWAS meta-analysis of smoking traits** as part of the **Latin American Genomic Consortium (LAGC)**.

**Project name:** *(to be defined)*  
**Authors:** Rafaella Ormond and Jaime Martinez-Magaña

📄 **Analysis plan and phenotype details:**  
👉 [View the full document here](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

---

## 📂 Repository Structure

The scripts are organized into the following steps:

### 🔹 `00QC/` – Quality Control
- `00arrayqc_preimputation/`: Pre-imputation QC  
- `01arrayqc_postimputation/`: Post-imputation QC

### 🔹 `01dataprep/` – Data Preparation
- `00dataprep_qc/`: QC preparation for analysis  
- `01dataprep_gwas/`: Data formatting for GWAS

### 🔹 `02GWAS/` – GWAS Execution  
Contains scripts for running GWAS using the following software:
- `00Regenie/`
- `01GMMAT/`
- `Saige/`

# Smoking GWAS LAGC

## Overview

This repository contains the analysis pipeline for conducting Genome-Wide Association Studies (GWAS) of smoking traits as part of the Meta-analysis efforts of the **Latin American Genomic Consortium (LAGC)**.

## Authors

- **Rafaella Ormond**
- **Jaime Martinez-Magaña**

## Documentation

For comprehensive details about the analysis plan, phenotypes, and methodology, please refer to our [detailed documentation](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing).

## Pipeline Structure

### 1. Quality Control (`00QC`)

#### 1.1 Pre-imputation QC (`00arrayqc_preimputation`)
Quality control procedures applied before imputation.

#### 1.2 Post-imputation QC (`01arrayqc_postimputation`)
Quality control procedures applied after imputation.

### 2. Data Preparation (`01dataprep`)

#### 2.1 QC Data Preparation (`00dataprep_qc`)
Data preparation focusing on quality control metrics.

#### 2.2 GWAS Data Preparation (`01dataprep_gwas`)
Data preparation specifically for GWAS analysis.

### 3. GWAS Analysis (`02GWAS`)

Genome-Wide Association Studies using the following software tools:

#### 3.1 Regenie (`00Regenie`)
GWAS analysis using the Regenie software package.

#### 3.2 GMMAT (`01GMMAT`)
GWAS analysis using the GMMAT (Generalized Mixed Model Association Test) software.

#### 3.3 SAIGE (`Saige`)
GWAS analysis using the SAIGE (Scalable and Accurate Implementation of Generalized mixed model) software.

## Getting Started

1. Clone this repository
2. Follow the analysis steps in numerical order
3. Refer to individual script documentation for specific parameters and requirements
4. Consult the linked documentation for detailed methodology

## Contact

For questions or collaboration inquiries, please contact the authors or refer to the LAGC consortium documentation.

---

*This project is part of the Latin American Genomic Consortium (LAGC) meta-analysis efforts.*


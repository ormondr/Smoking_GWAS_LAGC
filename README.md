### Smoking GWAS in LAGC<br>
### GWAS Consumo de Tabaco en LAGC<br>
### GWAS Consumo de Tabaco no LAGC<br>

**Authors:** [Rafaella Ormond](https://github.com/ormondr) and [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---
## 🌎 Available in different languages:

The scripts are available in **English**, **Spanish**, and **Portuguese**.  

***English:*** This repository contains the analysis workflow for the **GWAS meta-analysis of smoking traits** as part of the **Latin American Genomic Consortium (LAGC)[LINK]()**

***Español:*** Este repositorio contiene el flujo de trabajo para el **Meta-análisis de GWAS del consumo de Tabaco** como parte del **Latin American Genomic Consoritium (LAGC) [LINK]()**

***Português:*** Este repositório contem o fluxo de trabaho para a **Meta-análise de GWAS de consumo de Tabaco** como parte do **Latin American Genomic Consoritium (LAGC) [LINK]()**


**Analysis plan and phenotype details:**  
📄 [View the full document here](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

--- 
## Repository Structure

***English:*** <span style="color:red">Each language path has exactly the same repository structure. The explanation of each step will be inside of each script (Jupyter notebook format) </span> 
The scripts are organized into the following steps (inside the selected language folder):

- ***`English/`*** 
- `Espanol/`
- `Portugues/`

  ***Español:*** Cada carpeta de idioma tiene exactamente la misma estructura de repositorio (en rojo)  
Por favor, seleccione la carpeta del idioma deseado  
La explicación de cada paso estará dentro de cada script (en formato Jupyter notebook) (en rojo)  
Los scripts están organizados en los siguientes pasos (dentro de la carpeta de idioma seleccionada):

- `English/`
- ***`Espanol/`*** 
- `Portugues/`

***Português:*** Cada pasta de idioma possui exatamente a mesma estrutura de repositório (em vermelho)  
Por favor, selecione a pasta do idioma desejado  
A explicação de cada etapa estará dentro de cada script (no formato Jupyter notebook) (em vermelho)  
Os scripts estão organizados nas seguintes etapas (dentro da pasta de idioma selecionada):

- `English/`
- `Espanol/`
- ***`Portugues/`*** 

--- 
### 🌎 `English/`

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

---
### 🌎 `Espanol/`

### Control de Calidad (`00QC/`)
- `00arrayqc_preimputation/`: Control de calidad antes de la imputación  
- `01arrayqc_postimputation/`: Control de calidad después de la imputación

### Preparación de Datos (`01PC/`)
- `00PCAir/`: Cálculo de componentes principales para el análisis

### Preparación de Datos (`02dataprep/`)
- `00dataprep_gwas/`: Formateo de datos para GWAS

### Ejecución de GWAS (`03GWAS/`)
Contiene scripts para ejecutar GWAS utilizando el siguiente software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`
  
---
### 🌎 `Portugues/`

### Controle de Qualidade (`00QC/`)
- `00arrayqc_preimputation/`: Controle de qualidade antes da imputação  
- `01arrayqc_postimputation/`: Controle de qualidade após a imputação

### Preparação de Dados (`01PC/`)
- `00PCAir/`: Cálculo dos componentes principais para a análise

### Preparação de Dados (`02dataprep/`)
- `00dataprep_gwas/`: Formatação dos dados para GWAS

### Execução de GWAS (`03GWAS/`)
Contém scripts para rodar GWAS utilizando o seguinte software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`


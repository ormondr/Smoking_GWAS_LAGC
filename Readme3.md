---
### 🌎 Available in different languages:
The scripts are available in **English**, **Spanish**, and **Portuguese**.<br>

**Authors:** [Rafaella Ormond](https://github.com/ormondr) and [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---

## Smoking GWAS in LAGC<br>
***English:*** This repository contains the analysis workflow for the **GWAS meta-analysis of smoking traits** as part of the **Latin American Genomic Consortium (LAGC) [LINK](https://www.latinamericangenomicsconsortium.org/pt)**<br>
**Analysis plan and phenotype details:**
📄 [View the full document here](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

### Repository Structure
***English:*** ❗Each language folder has exactly the same repository structure.  
The explanation for each step is provided inside each script (Jupyter Notebook format). As pastas com cada linguagem são mostradas abaixo.
- Access scripts here: [`English/`](./English/)

---

## GWAS Consumo de Tabaco en LAGC<br>
***Español:*** Este repositorio contiene el flujo de trabajo para el **Meta-análisis de GWAS del consumo de Tabaco** como parte del **Latin American Genomic Consoritium (LAGC) [LINK](https://www.latinamericangenomicsconsortium.org/pt)**<br>
**Plan de análisis y detalles del fenotipo:**
📄 [Ver el documento completo aquí](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

### Estructura del repositorio
***Español:*** ❗Cada carpeta de idioma tiene exactamente la misma estructura de repositorio.  
La explicación de cada paso está incluida dentro de cada script (formato Jupyter Notebook). A continuación se muestran las carpetas con cada idioma.
- Accesar codigos aqui: [`Espanol/`](./Espanol/)

---

## GWAS Consumo de Tabaco no LAGC<br>
***Português:*** Este repositório contém o fluxo de trabalho para a **Meta-análise do GWAS sobre o consumo de tabaco** como parte do **Consórcio Genômico Latino-Americano (LAGC) [LINK](https://www.latinamericangenomicsconsortium.org/pt)**<br>
**Plano de análise e detalhes do fenótipo:**
📄 [Visualizar o documento completo aqui](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

### Estrutura de repositório
***Português:*** ❗Cada pasta de idioma possui exatamente a mesma estrutura de repositório.  
A explicação de cada etapa está incluída dentro de cada script (formato Jupyter Notebook). The folders with each language are shown below.
- Accesar scripts aqui: [`Portugues/`](./Portugues/)


---

| Folder/ Carpeta/ Pasta  | English                             | Español                                      | Português                                  |
|-------------------------|-------------------------------------|----------------------------------------------|--------------------------------------------|
| `00QC/`                 | Quality Control                     | Control de calidad                           | Controle de qualidade                      |
| `00QC/00arrayqc_preimputation/` | Pre-imputation QC                  | Control de calidad antes de la imputación   | Controle de qualidade antes da imputação  |
| `00QC/01arrayqc_postimputation/`| Post-imputation QC                 | Control de calidad después de la imputación | Controle de qualidade após a imputação    |
| `01PC/`         | Principal Components Calculation    | Cálculo de componentes principales           | Cálculo dos componentes principais         |
| `01PC/00PCAir/`         | PCAir   | PCAir   | PCAir |
| `02dataprep/` | Data preparation          | Preparación de datos                 | Preparação de dados
| `02dataprep/00dataprep_gwas/` | Data formatting for GWAS          | Formato para datos para GWAS                  | Formatação dos dados para GWAS          |
| `03GWAS/`      | Genome Wide Association Studies pipelines | Tuberias de Estudios de Asociación del Genoma Completo  |  Pipelines de Estudos de Associação do Genoma Completo |
| `03GWAS/00Regenie/`      | Regenie                             | Regenie                                      | Regenie                                    |
| `03GWAS/01GMMAT/`        | GMMAT                               | GMMAT                                        | GMMAT                                      |
| `03GWAS/02Saige/`        | SAIGE                               | SAIGE                                        | SAIGE                                      |

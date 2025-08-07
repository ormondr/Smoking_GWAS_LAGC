## GWAS Consumo de Tabaco no LAGC<br>
**Authores:** [Rafaella Ormond](https://github.com/ormondr) e [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---
Este repositório contém o fluxo de trabalho para a **Meta-análise do GWAS sobre o consumo de tabaco** como parte do **Consórcio Genômico Latino-Americano (LAGC) [LINK](https://www.latinamericangenomicsconsortium.org/pt)**<br>
**Plano de análise e detalhes do fenótipo:**
📄 [Visualizar o documento completo aqui](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

### Estrutura de repositório

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

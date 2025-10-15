## GWAS Consumo de Tabaco no LAGC<br>
**Authores:** [Rafaella Ormond](https://github.com/ormondr) e [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---

Para maiores informações sobre os fenótipos consultar o siguinte **Plano de análises:**

📄 [Consultar Plano de análises aqui](https://docs.google.com/document/d/14OkYgT9bguH8ciYjkQ8W09lsi9ZGiRy0fg5WS8MDcNA/edit?tab=t.0)

---
### Estrutura de repositório

### Controle de Qualidade (`00QC/`)
- `00arrayqc_preimputation/`: Controle de qualidade antes da imputação  
- `01arrayqc_postimputation/`: Controle de qualidade após a imputação

### Preparação de Dados (`01PC/`)
- `00PCAir/`: Cálculo dos componentes principais para a análise

### Execução de GWAS (`02GWAS/`)
Contém scripts para rodar GWAS utilizando o seguinte software:
- `00Regenie/`
- `01GMMAT/`
- `02Saige/`

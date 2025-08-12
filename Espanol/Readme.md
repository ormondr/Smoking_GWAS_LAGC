## GWAS Consumo de Tabaco en LAGC<br>
**Autores:** [Rafaella Ormond](https://github.com/ormondr) y [Jose Jaime Martinez-Magaña](https://github.com/martinezjaime)

---

Para mayor información sobre los fenotipos consultar el siguiente **Plan de análisis:**

📄 [Consultar Plan de análisis aquí](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)

---

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

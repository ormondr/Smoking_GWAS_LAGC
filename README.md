# Smoking_GWAS_LAGC

This path is the analysis flow to run the GWAS for the Meta-analysis efforts of genome-wide association studies of smoking traits in the Latin American Genomic Consortium (LAGC)<br>
Project name ""<br>
**Authors: Rafaella Ormond and Jaime Martinez-Magaña**

The analysis Plan and all the details about phenotypes and analysis also can be found on [this link](https://docs.google.com/document/d/1RzD5kBlj9rfiomda1G3NfxYDXLdmIUO7VX0cSNj70Kk/edit?usp=sharing)<br>

The scripts have the follow steps:<br>
1)00QC: Quality control
  1.1)00arrayqc_preimputation: quality control pre-imputation
  1.2)01arrayqc_postimputation: quality control post-imputation
2)01dataprep
  2.1)00dataprep_qc
  2.2)01dataprep_gwas
3)02GWAS: Genome-Wide Association scripts using the follow softwares:
  3.1)00Regenie
  3.2)01GMMAT
  3.3)Saige


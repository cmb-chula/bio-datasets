# A collection of interesting biological datasets for computationl biology analysis and machine learning model development

*Work in Progress* - Last updated: January 10, 2021

---
## Molecular Biology
1. [A curated benchmark of enhancer-gene interactions for evaluating enhancer-target gene prediction methods](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1924-8)
   - **Decription:** Benchmark of candidate Enhancer-Gene Interactions (BENGI) that integrate Registry of cCREs with experimentally derived 3D chromatin interactions, genetic interactions, and CRISPR/dCAS9 perturbations in 21 datasets across 13 biosamples
   - **Date:** Jan 2020
   - **Link:** [GitHub](https://github.com/weng-lab/BENGI), ENCODE and various databases
   - **Size:** 162,000 unique cCRE-gene pairs across the 13 biosamples
   
2. [Large database for the analysis and prediction of spliced and non-spliced peptide generation by proteasomes](https://www.nature.com/articles/s41597-020-0487-6)
   - **Decription:** In vitro proteasome digestion of 55 synthetic polypeptides followed by peptide product identification with mass spectrometry
   - **Date:** May 2020
   - **Link:** [Mendeley](https://data.mendeley.com/datasets/nr7cs764rc/1) and PRIDE PXD016782 (raw mass spectrometry data)
   - **Size:** 15,028 spliced and 7,305 non-spliced peptide products

---
## Single-Cell Transcriptomics
1. [Benchmarking single-cell RNA-sequencing protocols for cell atlas projects](https://www.nature.com/articles/s41587-020-0469-4)
   - **Decription:** Benchmark dataset of 13 commonly-used scRNA-seq protocols on samples consisted of human PBMC (60%), mouse colon cells (30%), and various cell lines
   - **Date:** Apr 2020
   - **Link:** [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE133549)
   - **Size:** Transcriptoics data for ~3,000 cell for each protocol (raw sequencing data)

---
## Drug
1. [Prediction of drug combination effects with a minimal set of experiments](https://www.nature.com/articles/s42256-019-0122-4)
   - **Decription:** A compendium of 23,595 drug combination matrices tested in various cancer cell lines and malaria and Ebola infection models
   - **Date:** Dec 2019
   - **Link:** [GitHub](https://github.com/IanevskiAleksandr/DECREASE/tree/master/210_Novel_Anticancer_combinations), [web tool](http://decrease.fimm.fi/data_availability), various publications and databases
   - **Size:** 23,595 drug combination matrices tested in cancer cell lines and malaria and Ebola infection models
   
2. [Community assessment to advance computational prediction of cancer drug combinations in a pharmacogenomic screen](https://www.nature.com/articles/s41467-019-09799-2)
   - **Decription:** Data and competition result from AstraZeneca's DREAM challenge to predict effect of drug combinations
   - **Date:** June 2019
   - **Link:** [Synapes](https://www.synapse.org/DrugCombinationChallenge), [AstraZeneca](https://openinnovation.astrazeneca.com/data-library.html), various databases
   - **Size:** 11,576 experiments from 910 drug combinations across 85 cancer cell lines

3. [Extending the small-molecule similarity principle to all levels of biology with the Chemical Checker](https://www.nature.com/articles/s41587-020-0502-7)
   - **Decription:** A collection of structural, chemical, and biological properties of ~800,000 small molecules
   - **Date:** May 2020
   - **Link:** [ChemicalChecker](https://chemicalchecker.org) and [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE137202)
   - **Size:** 25 properties of up to 778,460 small molecules (some features are not available for all small molecules)
   
4. [Predicting drug–protein interaction using quasi-visual question answering system](https://www.nature.com/articles/s42256-020-0152-y)
   - **Decription:** An end-to-end deep learning approach for predicting drug-protein interaction. Also describe three public datasets.
   - **Date:** Feb 2020
   - **Link:** [DUD-E](https://pubs.acs.org/doi/10.1021/jm300687e), [BindingDB](https://academic.oup.com/nar/article/44/D1/D1045/2502601), and [Negative samples](https://academic.oup.com/bioinformatics/article/31/12/i221/216307)
   - **Size:** Combined 62,392 positive interactions and > 1.4M negative interactions

---
## Cancer
1. [A deep learning system accurately classifies primary and metastatic cancers using passenger mutation patterns](https://www.nature.com/articles/s41467-019-13825-8)
   - **Decription:** Patterns of somatic passenger mutations detected in whole genome sequencing (WGS) of 2606 tumours representing 24 common cancer types produced by the PCAWG Consortium
   - **Date:** Feb 2020
   - **Link:** [PCAWG Consortium](https://dcc.icgc.org/releases/PCAWG), various databases
   - **Size:** Genetic mutations of 2,606 tumours from 24 cancer types
   
2. [Multi-omic and multi-view clustering algorithms: review and cancer benchmark](https://academic.oup.com/nar/article/46/20/10546/5123392)
   - **Decription:** Benchmarking of methods to integrate multi-omics data (gene expression, miRNA expression, and DNA methylation) to identify distinct cancer patient groups in TCGA dataset
   - **Date:** Nov 2018
   - **Link:** [Ron Shamir's Lab](http://acgt.cs.tau.ac.il/multi_omic_benchmark/download.html)
   - **Size:** 170-621 patients each from 10 cancer types (processed data)

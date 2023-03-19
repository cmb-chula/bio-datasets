# A collection of interesting biological datasets for computationl biology analysis and machine learning model development

*Work in Progress* - Last updated: January 10, 2021

---
## Molecular Biology
1. [A curated benchmark of enhancer-gene interactions for evaluating enhancer-target gene prediction methods](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1924-8)
   - **Description:** Benchmark of candidate Enhancer-Gene Interactions (BENGI) that integrate Registry of cCREs with experimentally derived 3D chromatin interactions, genetic interactions, and CRISPR/dCAS9 perturbations in 21 datasets across 13 biosamples
   - **Date:** Jan 2020
   - **Link:** [GitHub](https://github.com/weng-lab/BENGI), ENCODE and various databases
   - **Size:** 162,000 unique cCRE-gene pairs across the 13 biosamples
   
2. [Large database for the analysis and prediction of spliced and non-spliced peptide generation by proteasomes](https://www.nature.com/articles/s41597-020-0487-6)
   - **Description:** In vitro proteasome digestion of 55 synthetic polypeptides followed by peptide product identification with mass spectrometry
   - **Date:** May 2020
   - **Link:** [Mendeley](https://data.mendeley.com/datasets/nr7cs764rc/1) and PRIDE PXD016782 (raw mass spectrometry data)
   - **Size:** 15,028 spliced and 7,305 non-spliced peptide products

---
## Single-Cell Transcriptomics
1. [Benchmarking single-cell RNA-sequencing protocols for cell atlas projects](https://www.nature.com/articles/s41587-020-0469-4)
   - **Description:** Benchmark dataset of 13 commonly-used scRNA-seq protocols on samples consisted of human PBMC (60%), mouse colon cells (30%), and various cell lines
   - **Date:** Apr 2020
   - **Link:** [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE133549)
   - **Size:** Transcriptoics data for ~3,000 cell for each protocol (raw sequencing data)

---
## Drug
1. [Prediction of drug combination effects with a minimal set of experiments](https://www.nature.com/articles/s42256-019-0122-4)
   - **Description:** A compendium of 23,595 drug combination matrices tested in various cancer cell lines and malaria and Ebola infection models
   - **Date:** Dec 2019
   - **Link:** [GitHub](https://github.com/IanevskiAleksandr/DECREASE/tree/master/210_Novel_Anticancer_combinations), [web tool](http://decrease.fimm.fi/data_availability), various publications and databases
   - **Size:** 23,595 drug combination matrices tested in cancer cell lines and malaria and Ebola infection models
   
2. [Community assessment to advance computational prediction of cancer drug combinations in a pharmacogenomic screen](https://www.nature.com/articles/s41467-019-09799-2)
   - **Description:** Data and competition result from AstraZeneca's DREAM challenge to predict effect of drug combinations
   - **Date:** June 2019
   - **Link:** [Synapes](https://www.synapse.org/DrugCombinationChallenge), [AstraZeneca](https://openinnovation.astrazeneca.com/data-library.html), various databases
   - **Size:** 11,576 experiments from 910 drug combinations across 85 cancer cell lines

3. [Extending the small-molecule similarity principle to all levels of biology with the Chemical Checker](https://www.nature.com/articles/s41587-020-0502-7)
   - **Description:** A collection of structural, chemical, and biological properties of ~800,000 small molecules
   - **Date:** May 2020
   - **Link:** [ChemicalChecker](https://chemicalchecker.org) and [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE137202)
   - **Size:** 25 properties of up to 778,460 small molecules (some features are not available for all small molecules)
   
4. [Predicting drug–protein interaction using quasi-visual question answering system](https://www.nature.com/articles/s42256-020-0152-y)
   - **Description:** An end-to-end deep learning approach for predicting drug-protein interaction. Also describe three public datasets.
   - **Date:** Feb 2020
   - **Link:** [DUD-E](https://pubs.acs.org/doi/10.1021/jm300687e), [BindingDB](https://academic.oup.com/nar/article/44/D1/D1045/2502601), and [Negative samples](https://academic.oup.com/bioinformatics/article/31/12/i221/216307)
   - **Size:** Combined 62,392 positive interactions and > 1.4M negative interactions

---
## Cancer
1. [A deep learning system accurately classifies primary and metastatic cancers using passenger mutation patterns](https://www.nature.com/articles/s41467-019-13825-8)
   - **Description:** Patterns of somatic passenger mutations detected in whole genome sequencing (WGS) of 2606 tumours representing 24 common cancer types produced by the PCAWG Consortium
   - **Date:** Feb 2020
   - **Link:** [PCAWG Consortium](https://dcc.icgc.org/releases/PCAWG), various databases
   - **Size:** Genetic mutations of 2,606 tumours from 24 cancer types
   
2. [Multi-omic and multi-view clustering algorithms: review and cancer benchmark](https://academic.oup.com/nar/article/46/20/10546/5123392)
   - **Description:** Benchmarking of methods to integrate multi-omics data (gene expression, miRNA expression, and DNA methylation) to identify distinct cancer patient groups in TCGA dataset
   - **Date:** Nov 2018
   - **Link:** [Ron Shamir's Lab](http://acgt.cs.tau.ac.il/multi_omic_benchmark/download.html)
   - **Size:** 170-621 patients each from 10 cancer types (processed data)

---
## Chest radiographs
1. [NIH Chest 14 dataset](https://arxiv.org/abs/1705.02315v5)
   - **Description:** Chest x-ray images released by NIH. Disease annotations were automatically mined from radiologist reports. Around 1,000 images also contain bounding boxes indicating the location of lesions. Files provided in processed .png formats.
   - **Date:** 2017
   - **Link:** [Kaggle](https://www.kaggle.com/datasets/nih-chest-xrays/data), also available from many other clouds
   - **Size:** 112,120 chest x-ray images from 30,805 patients, with 14 disease class labels

2. [MIMIC-CXR-JPG, a large publicly available database of labeled chest radiographs](https://arxiv.org/abs/1901.07042v5)
   - **Description:** Chest x-ray images from Beth Israel Deaconess Medical Center. Disease annotations were automatically mined from radiologist reports. Files provided in processed .jpg formats. DICOM full-resolution files and radiologist reports are also available.
   - **Date:** 2019
   - **Link:** [PhysioNet](https://physionet.org/content/mimic-cxr/2.0.0/), access must be requested
   - **Size:** 377,110 chest x-ray images, with 14 disease class labels
  
3. [CheXpert: A Large Chest Radiograph Dataset with Uncertainty Labels and Expert Comparison](https://arxiv.org/abs/1901.07031v1)
   - **Description:** Chest x-ray images from Stanford University Medical Center. Disease annotations in the training set were automatically mined from radiologist reports. Disease annotation in the validation and test sets were obtained from experts. This is one of the datasets used to train NLP tools that automatically extract disease labels from radiologist reports.
   - **Date:** 2019
   - **Link:** [Stanford's AIM](https://stanfordaimi.azurewebsites.net/datasets/8cbd9ed4-2eb9-4565-affc-111cf4f7ebe2)
   - **Size:** 224,316 chest x-ray images from 65,240 patients, with 14 disease class labels
   
4. [VinDr-CXR: An open dataset of chest X-rays with radiologist’s annotations](https://www.nature.com/articles/s41597-022-01498-w)
   - **Description:** Chest x-ray images from Vin AI Group in Vietnam. This dataset is relatively small but each image was extensively annotated by multiple radiologists.
   - **Date:** 2022
   - **Link:** [PhysioNet](https://physionet.org/content/vindr-cxr/1.0.0/), [Kaggle](https://www.kaggle.com/c/vinbigdata-chest-xray-abnormalities-detection/)
   - **Size:** 18,000 chest x-ray images, with 14 disease class labels and **bounding boxes for lesion locations**.
   
5. [BRAX, Brazilian labeled chest x-ray dataset](https://www.nature.com/articles/s41597-022-01608-8)
   - **Description:** Chest x-ray images from Hospital Israelita Albert Einstein in Brazil. Disease annotations in the training set were automatically mined from radiologist reports (in Portugese). Both processed .png files and full-resolution DICOM files are available.
   - **Date:** 2022
   - **Link:** [PhysioNet](https://physionet.org/content/brax/1.1.0/)
   - **Size:** 40,967 chest x-ray images from 19,351 patients, with 14 disease class labels.
   
6. [PadChest: A large chest x-ray image dataset with multi-label annotated reports](https://www.sciencedirect.com/science/article/abs/pii/S1361841520301614)
   - **Description:** Chest x-ray images from San Juan Hospital in Spain. Extensive annotations with 174 radiographic findings, 19 differential diagnoses, and 104 anatomic locations organized as a hierarchical taxonomy were provided. 27% of the labelings performed by clinicians and the rest were predicted by an NLP model.
   - **Date:** 2020
   - **Link:** [BIMCV](https://bimcv.cipf.es/bimcv-projects/padchest/)
   - **Size:** 160,000 chest x-ray images from 67,000 patients.
   - **Extra:** A [COVID-19 extension](https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/) of this dataset is also available.

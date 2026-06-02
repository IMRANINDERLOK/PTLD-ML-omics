# 🧬 Network-Guided Transcriptomics of Tuberculosis Disease-State Transition

## 📌 Project Overview

This repository contains the computational resources for the study:

**Network-guided transcriptomics identifies drug-linked host-response biomarkers in tuberculosis disease-state transition**

The study focuses on identifying compact and interpretable host-response biomarkers that distinguish **active tuberculosis** from the **post-therapy state**. The analysis combines transcriptomic profiling, network-guided gene prioritization, external validation, machine learning classification, and drug-gene mapping.

## 🎯 Aim

To identify robust, interpretable, and drug-linked host-response biomarkers associated with tuberculosis disease-state transition.

## ✅ Objectives

* To analyze blood transcriptomic changes between active tuberculosis before therapy and the 12-month post-therapy state.

* To identify differentially expressed genes associated with tuberculosis treatment transition.

* To prioritize a compact biomarker panel using network-guided analysis.

* To validate the disease-state signature in an independent transcriptomic cohort.

* To evaluate the classification ability of prioritized biomarkers using machine learning models.

* To interpret key genes contributing to disease-state discrimination.

* To explore drug-gene links for prioritized host-response biomarkers.

## 🧪 Study Design

The study compares two tuberculosis disease states:

* **ATB_pre:** active tuberculosis before therapy
* **ATB_12m:** post-therapy tuberculosis state at 12 months

A discovery cohort was used to identify disease-state-associated genes, followed by independent validation to assess reproducibility and direction consistency.

## 🔬 Analysis Focus

This project focuses on host-response changes associated with tuberculosis treatment transition. The main biological signal identified in the study is linked to interferon-associated immune regulation, innate immune signalling, and inflammatory pathway modulation.

The final biomarker panel highlights **STAT1** and **GBP1** as central and reproducible markers of active disease resolution after therapy.

## 🧠 Computational Methods

The analysis includes:

* Differential gene expression analysis
* Network-guided biomarker prioritization
* Independent cohort validation
* Functional enrichment analysis
* Machine learning-based classification
* Feature-level model interpretation
* Drug-gene interaction mapping

## 📊 Key Findings

* The discovery analysis identified **1,086 differentially expressed genes** between ATB_pre and ATB_12m.

* External validation identified **320 overlapping genes** between discovery and validation cohorts.

* Directional consistency between cohorts reached **95.9%**, supporting the robustness of the disease-state signature.

* The final biomarker panel was dominated by interferon-associated genes.

* **STAT1** and **GBP1** emerged as the most stable and central biomarkers.

* Random Forest and support vector machine models achieved strong classification performance, with **AUC = 0.969**.

* Drug-gene mapping linked prioritized biomarkers with compounds such as **tretinoin** and **valproic acid**.

## 🧩 Biological Interpretation

The identified transcriptional signature reflects a reduction in active tuberculosis-associated immune activation after therapy. The dominance of interferon-linked genes suggests that active disease is characterized by strong innate and inflammatory host-response activity, which decreases after treatment.

The consistent reduction of **STAT1** and **GBP1** after therapy supports their value as compact and interpretable markers of tuberculosis disease-state transition.

## 💊 Drug-Linked Interpretation

Drug-gene mapping was used to explore whether prioritized biomarkers are connected to known pharmacological agents. This analysis linked key host-response genes with compounds such as **tretinoin** and **valproic acid**, placing the biomarker panel within a drug-linked framework.

These results should be interpreted as computational and hypothesis-generating, not as direct therapeutic evidence.

## 🛠️ Tools and Platforms

This project may include analysis using:

* R / RStudio
* Python / Google Colab
* GEOquery
* limma
* ggplot2
* pheatmap / ComplexHeatmap
* STRING
* Cytoscape
* Enrichr / g:Profiler
* DGIdb / CTD / DrugShot
* Scikit-learn
* SHAP or feature-importance analysis

## 📁 Repository Structure

```text
TB-DiseaseState-NetworkTranscriptomics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── scripts/
│   ├── preprocessing/
│   ├── differential_expression/
│   ├── validation/
│   ├── network_analysis/
│   ├── machine_learning/
│   └── drug_gene_mapping/
│
├── results/
│   ├── figures/
│   ├── tables/
│   └── supplementary_files/
│
├── docs/
│
├── README.md
└── LICENSE
```

## 👤 Author

**Mohd. Imran**

## 📄 License

This repository is intended for academic and research use. A suitable open-source license will be added before public release.

## 🤝 Citation

If you use this repository, workflow, or related results, please cite the associated publication once available.

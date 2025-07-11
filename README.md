# Cancer_Biology_Project
A study log and project documentation for my cancer biology and systems biology learning jorney.
# Systems Biology Course Project – Cancer Focus

This repository documents my progress in a project-oriented Systems Biology course focused on cancer and computational methods. The course integrates biological foundations with bioinformatics, programming (Python, R, JavaScript), and systems-level approaches to studying cancer development and progression.

---

## 📍 Current Progress

### ✅ Week 1 – Foundational Concepts

- Topics Covered:
  - Central Dogma of Molecular Biology
  - Gene expression and the flow of genetic information (DNA → RNA → Protein)
  - Transcription and translation machinery
  - Mutation types and their role in cancer development

- Mutation Types Discussed:
  - Point mutations (e.g., insertion, deletion, inversion)
  - Missense and silent mutations
  - How mutations affect gene expression and protein function in oncogenesis

---

## 📌 Course Objectives

As the course progresses, I will work on a cancer-related computational project that includes:

- Extracting and analyzing data from biological databases
- Applying bioinformatics tools to model gene interactions
- Using programming (Python, R, JavaScript) to interpret biological data
- Building a final presentation or paper based on findings

---

## 🔄 Next Steps

- Start hands-on activities with databases and cancer datasets
- Begin scripting analyses in Python or R
- Update this repository weekly with new sections and insights

---

## 🧠 Goal

To develop strong skills in systems biology and computational cancer research and showcase my active learning process as I pursue PhD opportunities in computational and cancer biology


#Add Session 2

# Session 2 – Exploring Gene-Disease Associations in Cancer

In this session, we concluded our discussions on gene mutations and began working with real databases to explore genetic mutations in cancer. We focused on tools and platforms that help investigate the relationships between genes and diseases, particularly within the context of oncology.

---

## 🧠 Topics Reviewed (Theory)

- Central dogma of biology: DNA → RNA → Protein
- Types of mutations:
  - Point mutations: substitution, insertion, deletion, inversion
  - Missense, nonsense, and silent mutations
- How these mutations can disrupt gene function and contribute to cancer

---

## 🧪 Databases & Tools Explored

### 1. HGNC (HUGO Gene Nomenclature Committee)
- Website providing official gene names and symbols
- Helps resolve ambiguity caused by multiple names for a single gene
- Useful for consistent gene identification across databases

### 2. dbGaP + PheGenI (Phenotype–Genotype Integrator)
- Provided by NCBI
- Allows you to input a disease and find related genes, or vice versa
- Useful in identifying genotype–phenotype correlations in cancer

### 3. OMIM (Online Mendelian Inheritance in Man)
- Database for mapping genes to human disorders
- Offers detailed descriptions of genetic conditions
- Especially useful for understanding hereditary cancer syndromes

### 4. DisGeNET
- Database focused on gene–disease associations
- Offers scores such as:
  - DSI (Disease Specificity Index): How specific a gene is to a given disease
  - DPI (Disease Pleiotropy Index): How many different diseases a gene is involved in
  - GDA Score: Strength of association between a gene and a disease
- Very useful for analyzing gene involvement across various cancers

---

## 🖼️ Screenshots / Hands-On Work

Below are screenshots from my work with the databases above:

![HGNC](https://github.com/user-attachments/assets/8e8a8814-5220-4306-980a-42ef67b8a210)

*Querying gene synonyms on HGNC*

![dbGap](https://github.com/user-attachments/assets/cd69cb25-b311-4539-a230-290a25d10c3a)

*Finding genes associated with breast cancer on PheGenI*

![Disgenet](https://github.com/user-attachments/assets/726c812c-d55d-4429-95ba-3a3cb95d2297)

*Using DisGeNET to explore gene–disease associations*

![OMIM](https://github.com/user-attachments/assets/c58afa13-3570-4356-ba9d-e201383cd364)

*Using OMIM to map genes to human disorders*

---

## 💡 Summary

This session provided a hands-on introduction to several major biomedical databases used in systems biology and cancer genomics. I learned how to navigate and cross-reference gene information and identify gene–disease links using publicly available tools.

---

📁 *All screenshots and queries are saved in this folder for documentation purposes.*

----------------------------------------------------------------------------------------

# 🧬 Session 3: Cancer Genomics Data Exploration and Mutation Analysis
 
Topic: Using The Cancer Genome Atlas (TCGA) and Genomic Data Commons (GDC) for Mutation and Survival Analysis

---

## 📌 Overview

In this session, I explored publicly available cancer genomics data platforms—primarily The Cancer Genome Atlas (TCGA) and the Genomic Data Commons (GDC) Data Portal—to understand how to analyze mutation frequencies, gene-specific information, and their impact on survival outcomes. I practiced using various built-in tools within these platforms, gaining hands-on experience with the practical application of genomic data in cancer research.

---

## 🗂️ Platforms & Tools Explored

### 1. 🔹 The Cancer Genome Atlas (TCGA)
- Started the session by reviewing the purpose and structure of TCGA.
- Captured a homepage screenshot of the TCGA portal.
- Understood its role in generating and housing large-scale cancer genomics datasets.

![the cancer genome atlas](https://github.com/user-attachments/assets/de48468a-58b3-4404-9bca-c6a0ce5d9301)


### 2. 🔹 GDC Data Portal
- Navigated the GDC Home Page.  
![Genomic Data Commons Data Portal](https://github.com/user-attachments/assets/27e701dc-d124-49d3-b902-9e297ed24c99)


#### Key tools used:
- 📊 Analysis Center – Interactive hub for exploring genetic alterations.
- 👥 Cohort Builder – Created patient cohorts using filters like:
  - Primary site (e.g., *Breast*)
  - Gender (e.g., *Female*)
  - Tumor descriptor (e.g., *Metastatic*) — *noted challenges with this filter’s availability*
- 🧬 Gene Search and Repository – Looked up specific genes and cancer types.
- 📁 Repository Tab – Learned to search and apply complex filters.

---

## 🔍 Mutation Frequency Analysis

Used the Mutation Frequency Tool within the GDC Analysis Center to:
- Identify most frequently mutated genes in breast cancer.
- View mutations in a lollipop chart format representing protein-level mutation distribution.

📸 *Example screenshot: Mutation Frequency for genes in breast cancer*  
![GDC Data Portal Genes](https://github.com/user-attachments/assets/80c605bc-5e35-4785-b73a-5d47953c22b9)


---

## 🧠 Understanding the Protein-Level Mutation Distribution

- Used the ProteinPaint visualization (Lollipop Plot) to:
  - View mutations along the length of proteins (e.g., EGFR).
  - Identify high-frequency mutations like EGFR p.L858R.

📸 *Example screenshot: Lollipop plot for EGFR* 
![Protein print](https://github.com/user-attachments/assets/e8767739-5c35-4ed3-9d8f-4dd9719f6e76)

---

## 📈 Mutation-Specific Survival Analysis

Learned how to:
- Click specific mutations in the Mutation Table.
- Automatically generate a Kaplan–Meier survival plot comparing:
  - Patients with that mutation.
  - Patients without the mutation.


🧪 *Key insight:* Different mutations in the same gene can have different effects on overall survival—highlighting the functional impact of mutation location and type.

---

## 📚 Tutorials & Self-Guided Exploration

- Watched official GDC tutorial videos to deepen understanding of the platform.
- Explored multiple cancers and genes to better grasp mutation frequency patterns and visualization tools.

---

## 🧾 Reflections & Takeaways

- While the GDC interface has evolved, it now presents a steeper learning curve. Key filters (e.g., Tumor Descriptor) and intuitive data access are more buried than in previous versions.
- The combination of protein visualization and mutation-specific survival plots is a powerful approach to understanding the real-world impact of genomic alterations.
- A working knowledge of the GDC Mutation Frequency Tool, ProteinPaint, and Kaplan–Meier plots is essential for anyone engaging with cancer genomic data.

---

## ✅ Key Skills Practiced

- Navigating real cancer genomics datasets.
- Filtering by clinical and genomic features (e.g., primary site, mutation type).
- Identifying gene-level mutations and their impact on survival.
- Using mutation frequency charts and survival plots in GDC.
- Integrating screenshots and documentation into a research portfolio.

---






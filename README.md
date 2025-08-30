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

Session 4  

## 📍 Topic
Exploring TumorPortal for cancer genetic mutation analysis.  

## 🔍 What I Learned
In this session, I worked with the TumorPortal database. This platform helps identify which genes are important in different cancers and reveals the most common mutations associated with them. It provides both gene-focused and tumor-focused perspectives, giving a comprehensive overview of the genetic landscape across cancers.  

![Tumor Portal Homepage](https://github.com/user-attachments/assets/75bfeb1a-e0e1-4244-b08d-061a8b3a95ca)

I learned two main ways of searching for data:  

1. Search by Tumor Type  
   - By selecting a cancer type (e.g., breast cancer, pancreatic cancer), TumorPortal provides a table of significant genes.  
   - Genes are categorized as:  
     - Highly Significant  
     - Significant  
     - Relatively significant (Near Significance)

![Tumor Portal Search by tumor](https://github.com/user-attachments/assets/8f23b0fe-2527-4523-9049-069aaa2b83f8)

   - The table also shows the mutation frequency and contribution of each gene to that cancer.  
   - A graphical overview is provided, which contains:  
     - Patient demographics (age, gender, histology, vital status, ethnicity).  
     - Gene mutation graphs showing:  
       - Frequency of gene mutations (most frequent at the top).  
       - Mutation types (missense, frameshift, loss-of-function, etc.).  
       - Number of patients affected per mutation.  
     - Copy number variation graphs, showing gene amplification or loss events.  

 ![Tumor Portal Search by tumor Graphs](https://github.com/user-attachments/assets/9ffdc90e-73df-40cb-ab0e-ba816ae24a59)


---

2. Search by Gene  
   - By entering a gene of interest, TumorPortal shows how that gene is mutated across cancers.  
   - Provides protein domain visualizations:  
     - Exact locations of mutations within the protein.  
     - Mutation types and their distribution.  
     - Filtering options to refine analysis.  
   - Includes links to external resources, such as the National Cancer Institute, for further reference.  

![Tumor Portal Search by Gene](https://github.com/user-attachments/assets/f6e5cdd0-d87b-4d5c-bc66-6a25d7e54930)

  
   - Example of mutation visualization graph when searching by gene  

---

## 📈 Key Takeaways
- TumorPortal is a powerful tool for exploring the relationship between cancers and genetic mutations.  
- It allows:  
  - Identifying which genes are mutated in specific cancers.  
  - Understanding the frequency and significance of mutations.  
  - Visualizing the mutation types, patient distribution, and copy number variations.  
  - Exploring protein domain-level effects of mutations.  
- Overall, this database provides quick yet detailed insights into the genetic drivers of cancer.  

📸 Final screenshot inserted here before conclusion:  
- Protein domain mutation visualization (Search by Gene)  

---

## 🖼️ Planned Screenshots for This Session
1. Homepage of TumorPortal  
2. Tumor search results (significant genes table)  
3. Tumor graph (mutation and CNV overview)  
4. Gene search graph (protein domain mutations)  

---

## ✅ Conclusion

This session highlighted how TumorPortal can give both a big-picture view of cancer genetics (by tumor type) and a focused gene-level view (by specific gene). Its combination of mutation frequency data, copy number variation, and protein domain visualizations makes it a very practical database for understanding cancer genomics.

------------

# Session 5 – Cancer Hotspots & Tumor Fusion Gene Data Portal

In this session, we explored two important databases that provide insight into how specific mutations and gene fusions contribute to cancer development. These resources focus on different aspects of cancer genomics: single-residue mutations and gene fusion events.

---

## Cancer Hotspots Database

Overview:  
The Cancer Hotspots database focuses on single-residue mutations within proteins that are statistically significant in cancer. It helps identify which amino acid changes occur at specific sites and how they contribute to cancer.

Key Learnings:
- The database highlights how mutations in different genes can lead to single-residue changes in the resulting proteins.  
- Example: A glycine at position 61 in a protein may mutate into several different amino acids, each contributing to different cancers with varying frequencies.  
- You can search by gene to find:
  - Lists of single-residue changes  
  - What residues are changing into  
  - The statistical frequency of these changes  
  - The percentage of cancers associated with each mutation  
- The database provides visual representations of these mutation events and their impact, making it easier to understand the data at a glance.

![Tumor Hotspots](https://github.com/user-attachments/assets/6018873f-2bed-4885-95dd-c8b6c308af4d)
  
Homepage of Cancer Hotspots database

![Tumor Hotspots (Stats)](https://github.com/user-attachments/assets/a199e90f-5808-40bc-a0ec-79cc1b1f6a3d)


Example visualization of residue-level mutations  

---

## Tumor Fusion Gene Data Portal

Overview:  
This portal focused on gene fusions in cancer. While it was freely available at the time of the workshop, it is no longer openly accessible. Nonetheless, the concepts it introduced remain highly valuable.

Key Learnings:
- Gene fusions occur when two different genes combine, creating abnormal hybrid genes that can drive cancer.  
- The portal allowed searches by:  
  - Cancer type → See which gene fusions are reported in a specific cancer (e.g., breast cancer).  
  - Gene → Find potential fusion partners and associated cancers.  
  - Gene pair → Check whether two specific genes have recorded fusions, and in which cancers.  
- This type of tool is especially useful in the experimental and hypothesis-building stages of research, providing insight into possible mechanisms for cancer progression.
 

---

## Conclusion

In summary, today’s session introduced two complementary approaches to studying cancer genomics:  
1. Cancer Hotspots – identifying statistically significant single-residue mutations in proteins and their associations with different cancers.  
2. Tumor Fusion Gene Data Portal – understanding gene fusions, their role in cancer development, and how to query them by cancer type, gene, or gene pairs.  

Both tools deepen our ability to link mutations and genomic rearrangements with cancer biology, offering valuable resources for hypothesis generation and experimental design.

------------------

# Session 6 – Predicting the Effects of Gene and Protein Mutations

In this session, we shifted from analyzing recorded mutations in databases to exploring tools that allow us to predict the potential effects of new mutations in genes and proteins. The focus was on understanding how a sequence alteration could impact protein behavior, even if that mutation has not been previously studied.

---

## Step 1: Extracting Sequences from NCBI

Overview:  
NCBI provides a wide range of information about genes, including their sequences, chromosomal location, gene names, associated studies, and disease links. For our purpose, we focused on extracting gene sequences to use in prediction tools.

Key Learnings:
- You can search for a specific gene and narrow results to a particular species.  
- NCBI offers access to different types of sequence data:  
  - GenBank → Contains raw, uncurated sequence submissions.  
  - RefSeq → Contains curated, reviewed sequences approved for reliability.  
  - FASTA → A machine-readable representation of the sequence.  
- Data management differences:  
  - US servers typically manage gene sequences.  
  - European servers often manage protein sequences.  

![NCBI](https://github.com/user-attachments/assets/e96c86fb-fd0c-49c9-920a-40cc71c65db7)

---

## Step 2: Extracting Protein Sequences from UniProt

Overview:  
UniProt provides comprehensive information about proteins, including their structure, mutations, functions, and disease associations. For predictions, we focused on extracting protein sequences.

Key Learnings:
- Search by protein name and filter by species to access detailed data.  
- UniProt provides:  
  - Information on mutations, pathology, and 3D structures.  
  - Different sequence representations:  
    - Human-readable format: amino acids grouped 10-by-10 for easier manual searching.  
    - FASTA format: a continuous sequence without spacing, suitable for computational use.  

![Uniprot](https://github.com/user-attachments/assets/66b4f758-7dd7-4e0f-b3e6-7fc539123af1)
Screenshot of UniProt protein sequence page. 

![Uniprot raw seq](https://github.com/user-attachments/assets/4b0945da-d84a-4e8a-be8e-a5c1dee48055)
Example of raw (10-by-10) sequence format.

![Uniprot FASTA seq](https://github.com/user-attachments/assets/6fe57377-dad7-4f0d-92e1-b33c77b8cad9)
Example of FASTA format.

---

## Step 3: Predicting Mutation Effects with PolyPhen-2

Overview:  
PolyPhen-2 is a tool that predicts how an amino acid substitution may impact protein structure and function.

Key Learnings:
- Input required:  
  - The FASTA sequence of the protein.  
  - The position of the amino acid you want to study.  
  - The original amino acid at that position.  
  - The new amino acid to test.  
- Output:  
  - A prediction of whether the mutation is benign, possibly damaging, or probably damaging.  
  - A downloadable result file summarizing the predicted effect.  

![Poly-Phen-2 hp](https://github.com/user-attachments/assets/d92354c1-aa2a-4903-907d-b084e4085621)
PolyPhen-2 input page.  

![Poly-Phen-2 results 1](https://github.com/user-attachments/assets/fd7a3f06-5c92-4c7a-b5bc-42965473fd30)
Example results page showing predictions.

![Poly-Phen-2 results 2](https://github.com/user-attachments/assets/9bcc31b7-af4a-4dbd-9f95-532d1c47581e)
Visualization of a predicted mutation effect.  

---

## Conclusion

This session introduced the concept of prediction in bioinformatics:  
1. From NCBI → Extract gene sequences (GenBank, RefSeq, FASTA).  
2. From UniProt → Extract protein sequences (raw vs. FASTA format).  
3. With PolyPhen-2 → Predict how specific amino acid substitutions affect protein function.  

By integrating sequence extraction with predictive tools, we can explore the potential impact of new or unstudied mutations, moving beyond recorded data to anticipate future discoveries in genomics and disease research.



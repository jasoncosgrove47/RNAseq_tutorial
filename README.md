# 🧬 RNAseq Tutorial

This tutorial demonstrates a complete **RNA-Seq analysis workflow** using Bioconductor packages.  

We’ll walk through:  

- ✅ Quality control of RNA-Seq data  
- ✅ Normalization and preprocessing  
- ✅ Differential expression analysis with **DESeq2**  
- ✅ Pathway enrichment to interpret biological meaning  
- ✅ Co-expression network analysis with **WGCNA**  

---

## 🎯 Learning Objective
By the end of this tutorial, you will be able to:  
- Identify **differentially expressed genes (DEGs)**  
- Interpret the **biological processes** regulated by these genes  

---

## 📊 Dataset Used

**Citation**  
Himes BE, Jiang X, Wagner P, *et al.* (2014).  
*RNA-Seq Transcriptome Profiling Identifies CRISPLD2 as a Glucocorticoid Responsive Gene that Modulates Cytokine Function in Airway Smooth Muscle Cells.*  
**PLoS One.** 9(6):e99625. PMID: [24926665](https://pubmed.ncbi.nlm.nih.gov/24926665/)  

**Data Source**  
- [Bioconductor airway package](http://bioconductor.org/packages/release/data/experiment/html/airway.html)  
- GEO Accession: [GSE52778](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52778)  

---

## 🧪 Experimental Design

- **Treatment**: Dexamethasone (1 μM, 18 hours) → potent synthetic glucocorticoid  
- **Control**: Untreated cells  
- **Goal**: Identify genes responsive to glucocorticoid treatment  

Glucocorticoids are widely used to treat **asthma and inflammatory airway diseases**.  
Understanding their molecular effects on airway smooth muscle cells provides insights into therapeutic mechanisms.  

---

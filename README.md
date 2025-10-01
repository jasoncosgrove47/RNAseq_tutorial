# RNAseq_tutorial
This tutorial demonstrates a complete RNA-Seq analysis workflow using Bioconductor packages. We’ll walk through:

- Quality control of RNA-Seq data
- Normalization and preprocessing
- Differential expression analysis with DESeq2
- Pathway enrichment to interpret biological meaning
- Co-expression network analysis with WGCNA
  
Learning Objective: By the end of this tutorial, you’ll understand how to identify differentially expressed genes and the biological processes they regulate.


# Dataset used in the tutorial

Citation: Himes BE, Jiang X, Wagner P, et al. (2014). “RNA-Seq Transcriptome Profiling Identifies CRISPLD2 as a Glucocorticoid Responsive Gene that Modulates Cytokine Function in Airway Smooth Muscle Cells.” PLoS One. 9(6):e99625. PMID: 24926665

Data Source: Bioconductor airway package | GEO: GSE52778
This study used RNA-Seq to characterize transcriptomic changes in four primary human airway smooth muscle (ASM) cell lines treated with:

Treatment: Dexamethasone (1 μM, 18 hours) — a potent synthetic glucocorticoid
Control: Untreated cells
Goal: Identify genes responsive to glucocorticoid treatment
Glucocorticoids are commonly used to treat asthma and other inflammatory airway diseases. Understanding their molecular effects on airway smooth muscle cells provides insights into therapeutic mechanisms.

# Integrating Graph Network Annotations and Structural Similarity Data to Uncover Photosynthesis Gene Functions


## Introduction
This project investigates high-confidence candidate photosynthesis genes in *Chlamydomonas reinhardtii* using a multi-omics, data-driven approach. By integrating graph network analysis and structural similarity pipelines, the goal is to better understand and predict the functions of previously uncharacterized genes involved in photosynthesis.


📄 **Full Report:** [View here](Chlamy_Final_Paper.pdf)


## Technologies 
- **Python**
- **Cytoscape** (graph network visualization)
- **FoldSeek** (structural alignment)
- **BLAST** (sequence similarity search)
- **ProteinCartography Pipeline**
- **AlphaFold Databases**
- **Plotly** (interactive visualization)
- **UCSF Chimera** (3D structure analysis)
- **High Performance Computing (HPC)**


## Features
- Construction of pairwise protein similarity graph networks  
- Structural similarity clustering using FoldSeek and TM-score metrics  
- Cross-species protein comparison using ProteinCartography  
- Interactive visualization of protein clusters (t-SNE, UMAP)  
- Functional inference of unknown genes using structural and network-based relationships  


## Process
1. Constructed graph networks where nodes represent proteins and edges represent structural similarity (FoldSeek e-values) using Cytoscape
2. Applied color overlays to analyze pathway and annotation patterns  
3. Ran ProteinCartography pipeline by Arcadia Science to compare proteins across species  
4. Generated similarity matrices and clustered proteins using Leiden algorithm  
5. Created interactive visualizations (t-SNE, UMAP) for exploration  
6. Analyzed structural similarity (TM-score, RMSD) between proteins  
7. Interpreted clusters to infer potential gene functions  


## Results
- Identified meaningful clustering patterns in protein graph networks  
- Observed that proteins in the same pathways often cluster together, but can also appear across multiple clusters due to functional complexity  
- Demonstrated that structural similarity can reveal relationships not captured by sequence similarity  
- Found strong structural similarity (TM-score ~0.81, low RMSD) between proteins across species despite low sequence similarity  
- Validated that structurally similar proteins often belong to photosynthetic organisms (Viridiplantae)  
- Showed that combining graph networks with structural pipelines improves functional annotation of unknown genes  


## What I Learned
- How to integrate multiple biological data sources for large-scale analysis  
- The importance of structural similarity in understanding protein function  
- Differences between sequence similarity and structural similarity  
- How to work with large biological datasets and HPC pipelines  
- The complexity of biological systems and gene function prediction  
- How to interpret and validate results using multiple analytical methods  

---

## How It Could Be Improved
- Apply the pipeline to all high-confidence genes at scale  
- Compare results with additional tools (e.g., alternative structural alignment methods)  
- Improve handling of intrinsically disordered proteins  
- Integrate additional biological datasets for stronger validation  
- Automate batch processing and visualization workflows  
- Enhance interpretability of large interactive protein maps  

*Developed as part of the SEED Scholars Program @ Lawrence Berkeley National Laboratory (Summer 2024)*

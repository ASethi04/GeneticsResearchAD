# FUNCTIONAL GENETIC BIOMARKERS OF ALZHEIMER’S DISEASE AND GENE EXPRESSION FROM PERIPHERAL BLOOD

### ABSTRACT

Detecting Alzheimer’s Disease (AD) at the earliest possible stage is key in advancing AD prevention and treatment, but is challenged by normal aging processes in addition to other neurodegenerative diseases. Recent genome-wide association studies (GWAS) have identified associated alleles, but it has been difficult to transition from non-coding genetic variants to underlying mechanisms of AD. Here, we sought to reveal functional genetic variants and diagnostic biomarkers underlying AD using machine learning techniques. We first developed a Random Forest (RF) classifier using blood microarray gene expression data from 744 participants in Alzheimer’s Disease Neuroimaging Initiative (ADNI) cohort. After initial feature selection, 5-fold cross-validation of the 100-gene RF classifier achieved an accuracy of 98.4%. The high accuracy of the RF classifier supports the possibility of a powerful and minimally invasive tool for screening of AD. Then, unsupervised clustering using Uniform Manifold Approximation and Projection (UMAP) and Hierarchical Density-Based Spatial-Clustering of Applications with Noise (HDBSCAN) were used to identify relationships among differentially expressed genes (DEGs) the RF selected. Results suggest downregulation of global sulfatase and oxidoreductase activities in AD through mutations in SUMF1 and SMOX respectively. Finally, we used Greedy Fast Causal Inference (GFCI) to find potential causes of AD within DEGs. In the causal graph, HLA-DPB1 emerges as the largest node connected to 75 out of 100 genes. HLA-DPB1 is downregulated and connected to AD through LDB3 and DYRK3 with no latent confounder. This study further advances understanding of molecular mechanisms underlying AD and provides potential gene targets for further experimentation.

The python notebooks in this repository are for the unsupervised clustering, random forest classification, data processing, and analysis.
Tetrad Causal Analysis files are also included.
Periperal blood gene expression data can be acquired by appling to the Alzheimer's Disease Neuroimaging Initiative (ADNI) database at http://adni.loni.usc.edu/

All the files are distributed under the MIT license.

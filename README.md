# Single Cell RNAseq data analysis scripts

*It is the reproduction of the ScRNA analysis for a Nat Comm paper: https://www.nature.com/articles/s41467-020-14296-y#Sec2
Wang, X., Xu, H., Cheng, C., Ji, Z., Zhao, H., Sheng, Y., ... & Zhu, H. H. (2020). Identification of a Zeb1 expressing basal stem cell subpopulation in the prostate. Nature communications, 11(1), 1-16. The detailed instructions are on the Youtube video: https://www.youtube.com/watch?v=IjJOTJsd4Mg*

The scRNAseq analysis pipeline has 4 steps as below: 
- 1: removal of poor quality cells and contaminated non-epithelial cells
- 2: clustering using Seurat
- 3: slingshot, calculating the pseudotime
- 4: clustering and pseudotime calculating

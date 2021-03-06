# VNC_scRNAseq

### This code is associated with the paper from Allen, Neville et al., "A single-cell transcriptomic atlas of the adult _Drosophila_ ventral nerve cord". eLife, 2020. http://doi.org/10.7554/eLife.54074

Analysis of scRNA-seq of the Drosophila melanogaster adult ventral nerve cord from females and males

Fastq sequencing data were processed using Drop-seq_tools v2.1.0, and was implemented with the '10x_parallelprocessing.sh', '10x_preprocessing.sh', and '10x_postprocessing.sh'. Resulting digital expression matrices were analysed with Seurat v2.3.4 using the 'R_preprocessing.R' script. The 'all_analysis.R' script contains information regarding the subsequent analysis for each figure of the manuscript. 'myDotPlot.R' is a modified version of Seurat v2.3.4's 'DotPlot' function to accept 3 colours when plotting the scaled expression. 'R_preprocessing_brain_data.R' script includes the analysis of the mid-brain drop-seq data (Croset et al 2018) and the brain 10x data (Davie et al 2018) to compare to the VNC data. 'sessionInfo.txt' contains the package version used in this analysis.  

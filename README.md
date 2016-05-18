# RUBIC-datasets
All datasets required for reproducing the results in the paper entitled "RUBIC identifies driver genes by detecting recurrent DNA copy number breaks" (submitted to Nature Communications)  
  
We compared RUBIC with GISTIC2 and RAIG on 3 SNP6 TCGA datasets, one TCGA whole exome sequencing dataset, one low coverage whole genome sequencing dataset and five simulated SNP6 datasets. The input files required by these three algorithms can be found in the following folder structure:  
-TCGA_SNP6  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-genome.info.6.0.hg19 ... (marker file for SNP6 platform)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-BRCA (folder with 1080 Breast cancer copy number profiles)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-GBM  (folder with  577 Glioblastoma copy number profiles)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-COAD (folder with  450 Colon Adenocarcinoma copy number profiles)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-BRCA_sim (folder with 5 X 1000 simulated Breast cancer copy number profiles)  
-TCGA_WES (necessary files required for deriving copy number profiles from TCGA exome sequencing data)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-markers.tsv (marker file for WES dataset)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-samples.tsv (list of 383 unique TCGA barcodes)  
-lcWGS (copy number profiles derived from an in-house low coverage whole genome sequencing dataset)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-markers.tsv (marker file for lcWGS dataset)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-BRCA (folder with 90 Breast cancer copy number profiles)  


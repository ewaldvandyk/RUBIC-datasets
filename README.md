# RUBIC-datasets
All datasets required for reproducing the results in the paper entitled "RUBIC identifies driver genes by detecting recurrent DNA copy number breaks" (submitted to Nature Communications)  
  
We compared RUBIC with GISTIC2 and RAIG on 3 SNP6 TCGA datasets, one TCGA whole exome sequencing dataset, one low coverage whole genome sequencing dataset and five simulated SNP6 datasets. The input files required by these three algorithms can be found in the following folder structure:  
-TCGA_SNP6  
  -genome.info.6.0.hg19 ... (marker file for SNP6 platform)  
  -BRCA (folder with 1080 Breast cancer copy number profiles)  
  -GBM  (folder with  577 Glioblastoma copy number profiles)  
  -COAD (folder with  450 Colon Adenocarcinoma copy number profiles)  
  -BRCA_sim (folder with 5 X 1000 simulated Breast cancer copy number profiles)  
-TCGA_WES (copy number profiles derived from TCGA whole exome sequencing data)  
  -markers.tsv (marker file for WES dataset)  
  -BRCA (folder with 383 Breast cancer copy number profiles)  
-lcWGS (copy number profiles derived from an in-house low coverage whole genome sequencing dataset)  
  -markers.tsv (marker file for lcWGS dataset)  
  -BRCA (folder with 90 Breast cancer copy number profiles)  


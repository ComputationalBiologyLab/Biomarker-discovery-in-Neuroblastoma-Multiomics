# Biomarker-discovery-in-Neuroblastoma-Multiomics
Code for replicating the study "A computational framework for biomarker discovery in Neuroblastoma ‎through multi-omics data"

### 1-Data retrieval (This step can be skipped, and use the files directly which are available in the the following link):
 https://drive.google.com/drive/folders/18UzhT5_4NNl4sfyfVDjdCbFAMner7NyL?usp=share_link 

Open SRC directory.

Create a data directory inside the SRC directory.

Open "Data_Retrieval.ipynb" with jupyter notebook.

Run all.

The following files will be saved in the working directory:

'samples.png'

'samples2.png'

'NBL_mRNA_FPKM.csv'

'NBL_miRNA_RPM.csv'

'NBL_methylation_beta_values.csv'

'TARGET-30-PAIFXV-01'

'NBL_methylation_detection_p_values.csv'

'NBL_clinical.csv'

'sums_of_samples_FPKM.png'

'NBL_mRNA_TPM.csv'

'sums_of_samples_TPM.png'


Figures are results.

Place the other files in the 'data/' directory.


### 2-Feature Selection:

Open SRC directory.

Open data directory.

In case step 1 was not performed, download the data from here: https://drive.google.com/drive/folders/18UzhT5_4NNl4sfyfVDjdCbFAMner7NyL?usp=share_link

Return to the SRC directory. 

Open "Feature_Selection.Rmd" with Rstudio.

Run all.

The following results will be saved in your working directory:


"check_normalization.png"

"SNFconv_error_T.png"

"SNFconv_error_K.png"

"SNFconv_error_alpha.png"

"displayClusters_group2.png"

"displayClusters_group3.png"

"displayClusters_group4.png"

"displayClusters_group5.png"

"displayClusters_group6.png"

"displayClusters_group7.png"

"DunnIndex.png"

"mRNA_features_ranks4clusters.csv"

"miRNA_features_ranks4clusters.csv"

"methyl_features_ranks4clusters.csv"

"mRNA_ranks_4clusters.png"

"miRNA_ranks_4clusters.png"

"methyl_ranks_4clusters.png"

"mRNA4_sig.csv"

"miRNA4_sig.csv"

"methyl4_sig.csv"

"common_gene_list.txt"

"miRNA_list.txt"

"Venn_mRNA_methyl.png"

### 3-Interaction Network Construction:


Open SRC directory.

Open "Interaction_Network_Construction.Rmd" with Rstudio.

Follow the instructions within the .Rmd file to download interaction databases.

Run all.

The following results will be saved in your working directory:


"FINAL_filtered_Interactions_transmirL2_tarbase_annotated.csv"

"FINAL_filtered_Interactions_transmirL2_tarbase_nodeAttributes_annotated.csv"


These files are used for network analysis using cytoscape.

### 4-Validation:

Open "Validation.Rmd" with Rstudio.

Make sure you have the following files in your working directory (they are available at: https://drive.google.com/drive/folders/18UzhT5_4NNl4sfyfVDjdCbFAMner7NyL?usp=share_link):

"Biomarkers.csv"

"NBL_mRNA_TPM.csv"

"NBL_miRNA_RPM.csv"

"TARGET-30-PALBFW-01_mRNA.csv"

"NBL_clinical.csv"

"GSE62564_SEQC_NB_RNA-Seq_log2RPM.txt"

"GSE62564_clinical.txt"

"refseqID2genesymbol.txt"

"GSE128004_RPKM-NB-exomalmiRNA.txt"


Run the Survival analysis section.

The following results will be saved in your working directory:

"OverallSurvival_hsa-mir-137_Mean.png"

"OverallSurvival_hsa-mir-421_Mean.png"

"OverallSurvival_hsa-mir-760_Mean.png"

"OverallSurvival_hsa-mir-940_Mean.png"

"OverallSurvival_hsa-mir-1305_Mean.png"

"OverallSurvival_hsa-mir-1976_Mean.png"

"OverallSurvival_hsa-mir-2110_Mean.png"

"OverallSurvival_MYCN_Mean.png"

"OverallSurvival_POU2F2_Mean.png"

"OverallSurvival_SPI1_Mean.png"

"automatic_survival_pvalues.csv"

Remove these files from working directory to avoid overwriting.

Run the remaining sections.

The following results will be saved in your working directory:

"OverallSurvival_MIR137_Mean.png"

"OverallSurvival_MIR421_Mean.png"

"OverallSurvival_MIR760_Mean.png"

"OverallSurvival_MIR940_Mean.png"

"OverallSurvival_MIR1305_Mean.png"

"OverallSurvival_MIR1976_Mean.png"

"OverallSurvival_MIR2110_Mean.png"

"OverallSurvival_MYCN_Mean.png"

"OverallSurvival_POU2F2_Mean.png"

"OverallSurvival_SPI1_Mean.png"

"automatic_survival_validation_pvalues.csv"

"Chi_square_test_results.csv"

"ROC_hsa-mir-137.png"

"ROC_hsa-mir-421.png"

"ROC_hsa-mir-760.png"

"ROC_hsa-mir-940.png"

"ROC_hsa-mir-1976.png"

"ROC_hsa-mir-2110.png"

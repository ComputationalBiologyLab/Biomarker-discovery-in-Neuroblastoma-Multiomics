# Biomarker-discovery-in-Neuroblastoma-Multiomics
Code for replicating the study "A computational framework for biomarker discovery in Neuroblastoma ‎through multi-omics data"

### 1-Data retrieval (This step can be ignored, as the resultant files are available in the SRC/data/ directory):

Open SRC directory.

Open with jupyter notebook.

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
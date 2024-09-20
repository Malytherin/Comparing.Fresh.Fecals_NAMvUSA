# Comparing.Fresh.Fecals_NAMvUSA
 Code for preprocessing FASTQ files and analysis to produce figures for the fresh fecal comparison objective of "Namibian Cheetahs Fecal Microbiota is More Stable During Degradation and More Diverse Compared to Ex Situ Cheetahs in the USA"
 
 ## Coding files
 1. Two.Pop.Comparisons_Preprocessing.Rmd - code for preprocessing unpaired FASTQ files for fresh samples from NAM and USA (dada2, decontam, build phylogenetic tree, create phyloseq files, calculate alpha diversity metrics)
 2.Two.Pop.Comparisons_Analyses.Rmd - code for statistical tests and visualizations of relative abundance and alpha and beta diversity
 3. CPTf23_Picrust2.ipynb - Jupyter Notebook file for running PICRUSt2
 4. CPTf23_Picrust2_categorize_by_function.Rmd - code for merging and categorizing Picrust output into level 1, 2, and 3 categories 
 5. CPTf23_ALDEx2_PICRUST.Rmd - code for statistical analyses and visualizations of picrust data at levels 1, 2, and 3
 
 ## Files for phyloseq object (needed for Analyses code if not building from scratch)
 1. CPTf23_featuretable_Nov23.csv - table of ASV counts by samples
 2. CPTf23_taxonomy_Nov23.csv - mapping file for ASV numbers to taxonomic classifications
 3. Metadata_CPT23_final.csv - metadata for samples
 4. CPTf_2023_DNAsequences.csv - DNA sequences for all ASVs
 5. CPTf23_cleanseqs_tree.nwk - phylogenetic tree of ASV sequences

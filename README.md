# Metagenomic analyses for a methane cycling microbial community
This GitHub page serves as a data and code repository for a metagenomic study conducted on the methane cycling microbial community of a landfill (link to the manuscript on biorXiv here: )

# How to use this repository
The major workflows for data analyses and visualizations have been organized into self-contained directories. Each directory contains an R markdown file (denoted by the file extension .rmd) that outlines the major steps taken in data analyses and visualization. The R markdown files contain a mix of bash and R code and all packages and software used in data analyses are noted in the R markdown files. Each directory contains the input files required to reproduce the data analyses and key figures in the manuscript. Example outputs have also been provided to facilitate reproducibility. Although all software and R packages used in data analyses are referenced in each markdwon file, we have included links to the GitHub pages for software used in this manuscript for convenience:
- DRAM: https://github.com/WrightonLabCSU/DRAM
- GToTree: https://github.com/AstrobioMike/GToTree
- ggtree: https://github.com/YuLab-SMU/ggtree

These directories have been designed so that users can find everything they need in one place to reproduce analyses. Portions of the R markdown file containing bash code will need to be input manually into a terminal window whereas the R code can be run directly in software such as R studio with outputs for data visualizations being sasved directly to the directory where the R markdown file is contained.

# Summary of directory contents
All markdown files refer to figures in line with manuscript. Figure numbers are keyed to the manuscript and supporting information. These directories contain (presented in the order as outputs appear in the manuscript):

- **Main_metagenomic_data_analyses**: This directorty includes workflows for creating visualizations that summarize metagenome-assembled-genome (MAG) coverage data and metabolic modeling information using outputs from DRAM. This directory can be used to reproduce **Figure 3**, **Figure 5**, **Figure S2**, and **Table S1** from the manuscript. 
- **Methanogen_metaanalyses**: This directory contains input data compiling the names of methanogenic taxa from previous landfill studies. The markdown file in this directory documents all data manipulation steps and R scripts used to produce **Figure 4** in the manuscript.
- **GToTree_Methanoperedenaceae_example**: This directory contains the code required to generate phylogenetic trees and metabolic models for genomes retrieved from the family *Methanoperedenaceae*. This is one example of the workflow that combines GToTree and DRAM to characterize the metabolic capacity of MAGs compared to previously sequenced representative available through the Genome Taxonomy Database (GTDB). This workflow was repeated for the family *Methylacidiphilaceae* in the manuscript. This directory can be used to produce **Figure S4** from the manuscript.
- **GToTree_Nevskiaceae_example**: This directory contains the code required for phylogenomic analyses using GToTree to identify biomarker genes in genomes from the family *Nevskiaceae* retrieved from GTDB. This is an example of the workflow that was applied to the families *Acetobacteraceae* and *Mycobacteriaceae* in the manuscript. This directory can be used to produce **Figure S6** in the manuscript.
- **Supplementary_files**: This is a directory that houses Supplemetary Files 1-7 referred to in the manuscript. Many of these supplementary files have been included in the repositories mentioned above for convenience. **Note:** File S2 has been re-configured as a Dropbox link to facilitate downloading the large annotation file output by DRAM (size = 1.22 Gb).


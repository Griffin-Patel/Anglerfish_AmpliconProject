# Analysis folder

This folder contains the main R Markdown files and their rendered HTML outputs for the anglerfish amplicon sequencing project. Each file represents one major step in the workflow, starting with sequence quality control and ending with the biological interpretation of the microbial communities associated with different anglerfish tissues.

## Files

- **00_FastQC/**  
  This folder contains the sequence quality control results, including the MultiQC report. It is mainly used to check how good the raw reads look before trimming and downstream analysis.

- **01_DADA2Anglerfish.Rmd / 01_DADA2Anglerfish.html**  
  This file runs the DADA2 workflow, including filtering, trimming, denoising, merging, and chimera removal. It shows how the raw sequencing reads were processed into ASVs.

- **02_Phyloseq_PreprocessingAnglerfish.Rmd / 02_Phyloseq_PreprocessingAnglerfish.html**  
  This file builds the phyloseq object and combines the ASV table, taxonomy, and metadata. It shows how the dataset was organized and cleaned up before downstream analysis.

- **03_PreProcessingAnglerfish.Rmd / 03_PreProcessingAnglerfish.html**  
  This file contains additional preprocessing and quality control steps after the phyloseq object was built. It shows how the final dataset was prepared for biodiversity and community analyses.

- **04_BiodiversityAnglerfish.Rmd / 04_BiodiversityAnglerfish.html**  
  This file focuses on alpha diversity using Hill numbers and related biodiversity analyses. It shows how microbial diversity changes between luminous and non-luminous anglerfish tissues.

- **05_Community_AnalysisAnglerfish.Rmd / 05_Community_AnalysisAnglerfish.html**  
  This file focuses on beta diversity and ordination analyses, including multivariate statistics. It shows how overall microbial community composition differs across tissue groups.

- **06_CompositionAnglerfish.Rmd / 06_CompositionAnglerfish.html**  
  This file looks at taxonomic composition at the phylum, genus, and ASV levels. It shows which microbial groups are most abundant and which taxa, especially Enterovibrio, are most relevant to the project question.

## Notes

Together, these files tell the full analysis story from raw reads to ecological interpretation.

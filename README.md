# Anglerfish_AmpliconProject
BIOMI6300 Amplicon Project

## Paper Information

**Paper Name:** Characterization of the microbiome and bioluminescent symbionts across life stages of Ceratioid Anglerfishes of the Gulf of Mexico

**Paper Link:** https://doi.org/10.1093/femsec/fiz146

## Project Background

Here I analyze 16S rRNA amplicon sequencing data from deep-sea anglerfish, in the suborder ceratioidei, to investigate how microbial communities differ across body tissue regions, with emphasis on the differences between luminous and non-luminous tissues. Ceratioid anglerfishes are known for their bioluminescent organs, including the esca and caruncles (the lure and accesory light organ), which may host specialized bacterial symbionts. Comparing these luminous tissues to non-luminous tissues such as skin, gut, gills, and illicium helps test whether bioluminescent organs are associated with distinct microbial communities.

## Scientific Question

Which bacterial taxa are differentially abundant between the light organs (esca and caruncle) and non-luminous body regions (e.g., skin, gut, gills, and illicium) of deep-sea anglerfishes in the suborder Ceratioidei?

## Hypotheses

**H0:** There is no difference in the abundance of microbial taxa between the light-producing and non-light-producing body regions of anglerfish.

**H1:** There is a measurably higher abundance of luminous symbiotic bacteria in light-producing tissues than in other body regions.

## Dataset Information

This project uses published Illumina amplicon sequencing data associated with ceratioid anglerfish tissues.

- **BioProject ID:** PRJNA514914
- **SRA Study:** SRP178885
- **SRR accession numbers:** SRR8438042–SRR8438158 (full accession table included in `data/metadata/SraRunTable.csv`)
- **Metadata file:** `data/metadata/SraRunTable.csv`

## 16S rRNA Amplicon Information

- **16S region:** V4
- **Forward primer:** 515F (`GTGYCAGCMGCCGCGGTAA`)
- **Reverse primer:** 806R (`GGACTACNVGGGTWTCTAAT`)

## Project Goals

The goals of this repository are to:

1. Assign ASVs and taxonomy using DADA2.
2. Build phyloseq objects and preprocess the data.
3. Evaluate biodiversity across tissue types.
4. Analyze microbial community composition with ordination and multivariate statistics.
5. Compare taxonomic composition across tissues.
6. Interpret the microbial patterns in the context of anglerfish bioluminescent symbiosis.

## Repository Structure

- `analysis/` contains R Markdown files and rendered HTML outputs
- `data/` contains metadata and intermediate project data objects
- `code/` contains helper functions and plotting settings
- `figures/` contains output figures from the analyses
- `presentation/` contains presentation materials


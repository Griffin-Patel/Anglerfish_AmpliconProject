# Data folder

This folder contains the metadata and intermediate data objects used throughout the anglerfish amplicon sequencing project.

## Contents

- **metadata/**  
  This folder contains the sample metadata used in the project.  
  - `SraRunTable.csv` includes the run accession numbers and sample information used to connect each sequencing file to tissue type and other study variables.

- **00_raw_gzipped_fastqs/**  
  This is the location for the raw compressed FASTQ files. Because large sequencing files can exceed GitHub size limits, they are not always tracked in the repository.

- **00_adapter_removed_fastqs/**  
  This folder contains or is intended to contain adapter-trimmed FASTQ files used for downstream sequence processing.

- **01_Quality_Trimming**  
  Contains data objects or outputs related to trimming and sequence quality control.

- **02_AssignASVs_Lecture / 03_PreProcessing / 04_Biodiversity / 05_Ordination**  
  These folders contain intermediate `.RData` files and other outputs generated at different steps of the workflow. They make it possible to continue later analyses without rerunning every earlier step from scratch.

## Notes

This folder stores the project inputs and intermediate outputs needed to keep the workflow reproducible.

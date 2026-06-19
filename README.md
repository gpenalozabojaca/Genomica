# Zamia Transcriptome Analysis Pipeline

This repository documents the bioinformatics workflow used for de novo transcriptome assembly, quality assessment, contamination filtering, and functional annotation of RNA-seq data from *Zamia* species.

The report integrates quality control (FastQC, Trimmomatic), transcriptome assembly (Trinity), assembly evaluation (TransRate and BUSCO), taxonomic filtering (BlobTools2), and downstream annotation procedures. All analyses were performed on a high-performance computing (HPC) environment using reproducible SLURM-based workflows.

The repository contains the analysis report, workflow documentation, scripts, figures, and summary tables required to reproduce and understand the analytical pipeline. Large intermediate files (e.g., FASTQ, BAM, and temporary outputs) are intentionally excluded from version control.

This project serves as a reproducible reference for transcriptomic analyses in non-model plant species and can be adapted for similar RNA-seq studies.

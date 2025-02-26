This repository contains raw and normalized gene-level count data, R markdown and CellProfiler markdown files used to run the analyses in the Cardozo et al (2025) paper.
RNA-sequencing from induced microglial-like cells (iMGs) cultured in Astrocyte Conditioned Media (ACM) from control- and schizophrenia-sourced hiPSC-derived astrocytes stimulated with TNF-a.

Sequencing files (.fastq) quality was analyzed using Fastqc, adapters and low quality reads removed using trimmomatic, transcriptomic aligned and mapped using STAR, and reads counted using featureCounts.

Raw gene-level counts relate to the direct results of featureCounts quantification.
Normalized gene-level counts refer to batch-effect removed and TMM normalized count data using RUV-seq.

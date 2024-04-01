
# Estrogen Response Genomic Peaks Analysis

## Overview
This project encompasses a comprehensive analysis of genomic data to identify peaks associated with estrogen response. Using data from SRA accessions SRR1021789 and SRR1021804, this study employs a suite of bioinformatics tools, including the sra-toolkit, fastqc, bowtie2, and MACS2, to elucidate the genomic landscape influenced by estrogen.

## Dataset
The analysis is based on publicly available data from the Sequence Read Archive (SRA), specifically the datasets SRR1021789 and SRR1021804. These datasets represent sequencing data pertinent to estrogen response studies.

## Methods
The methodology section outlines the step-by-step process of data acquisition, quality control, alignment, and peak calling. This section is crucial for reproducibility and transparency. Detailed commands and software versions ensure that other researchers can replicate the study.

### Data Acquisition
Data was downloaded using `sra-toolkit`'s `prefetch` tool and converted to FASTQ format with `fastq-dump`.

### Quality Control
Quality control checks were performed using `fastqc` to assess the integrity and quality of the sequencing data.

### Alignment
The `bowtie2` tool was employed for aligning sequencing reads to the human genome (hg19), preparing the data for peak analysis.

### Peak Calling
`MACS2` was used for calling peaks, identifying regions of significant enrichment associated with estrogen response.

## Conclusions
Summarize the study's outcomes, emphasizing the contribution to understanding estrogen's role in genomic regulation.

## How to Use
Instructions on how to replicate the analysis, including environment setup, data preparation, and command execution.

## Contact
For inquiries or collaborations, please contact Ilaha Musayeva at ilahamusayeva06@gmail.com.

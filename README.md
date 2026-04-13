# Project 1: NGS Variant Calling Pipeline

## Overview
An end-to-end somatic variant calling pipeline built for oncology genomics.
Processes raw WES sequencing data through QC, alignment, and variant calling
using industry-standard tools (BWA, GATK) orchestrated with Snakemake.

## Motivation
Clinical genomics labs like BillionToOne process tens of thousands of samples
to detect cancer-relevant mutations. This project replicates that production
pipeline architecture using publicly available TCGA tumor/normal WES data.

## Tools
- BWA — read alignment to reference genome
- GATK HaplotypeCaller — variant calling
- samtools — BAM file processing
- Snakemake — workflow orchestration
- Python — pipeline automation and data engineering

## Data
Public WES data from The Cancer Genome Atlas (TCGA) via GDC portal.

## Author
Kyle Andrew Nunez | github.com/kyleandrewnunez

# Hail analysis of 1000 Genomes VCF

## Description

This repository written in PySpark contains the process to process a VCF with the the Broad Institute's Hail platform. Hail is written on top of Apache Spark, and as of this writing, is on its second version, which allows the processing of multiple VCFs simultaneously.  

## Usage

1. Process 1000 Genomes VCF.

> Prelim: set up hail context and Spark. download your vcf. 

Step 1:
> load vcf

Step 2:
> split multiallelic variants

Step 3: 
> run VEP

Step 4:
> explore data

Result:
Your vcf file is loaded and annotated


2. Hail GWAS tutorial includes:

> Loading data

> Variant annotations

> QC metrics

> running the GWAS

> PCA

> Regression

> Rare variant analysis

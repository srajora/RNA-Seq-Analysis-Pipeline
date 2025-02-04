# RNA-Seq-Analysis-Pipeline
A fully automated pipeline for processing and analyzing RNA-Seq data using Snakemake, Python, and R. This workflow covers quality control, read alignment, expression quantification, and differential gene expression analysis.
Overview
This project implements an automated pipeline for RNA-Seq data analysis, covering preprocessing, quality control, alignment, and differential expression analysis.

Workflow Steps
1️⃣ Preprocessing & Quality Control

FastQC: Assess sequence quality.
Trimmomatic: Trim low-quality reads and adapters.
2️⃣ Alignment & Mapping

HISAT2/STAR: Align reads to the reference genome.
Samtools: Convert and process BAM files.
3️⃣ Gene Expression Quantification

FeatureCounts/HTSeq: Count mapped reads per gene.
4️⃣ Differential Expression Analysis

DESeq2/edgeR: Identify differentially expressed genes.
Generate volcano plots and heatmaps.
5️⃣ Functional Analysis

Gene Ontology (GO) and KEGG pathway analysis.
6️⃣ Automation

Snakemake workflow to streamline all steps.

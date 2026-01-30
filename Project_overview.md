# Project Overview

This repository contains a set of focused notebooks demonstrating practical tasks in bioinformatics and
computational biology.

## Notebook summary

### — DNA Sequence Analysis
- Counts unique characters (A/T/C/G)
- Computes nucleotide frequencies and proportions
- Pattern replacement (e.g., convert a motif to lowercase) and coordinate reporting
- Trimming subsequences and validating downstream transformations

### — FASTA Parsing (RAD21)
- Parses FASTA using Biopython
- Builds a dictionary of full headers → sequences
- Computes sequence length list (sorted/unsorted)
- Extracts the RAD21_MOUSE record and exports it in FASTA format

### — Gene Expression Statistics + I/O
- Reads expression matrix to dictionary
- Computes min/max/mean/sum/variance per gene
- Sorts genes by mean expression (Top 10)
- Sorts genes by variance (Top 10)
- Writes summary results to output files

### — Genome Annotation (GFF) Parsing
- Parses GFF for `gene` features
- Extracts gene ID, chromosome, start, end coordinates
- Random sampling to generate multiple temporary gene lists for downstream analysis

### — Local BLAST Workflow
- Builds local protein BLAST database from FASTA
- Runs `blastp`
- Parses BLAST XML output using Biopython NCBIXML

### — Visualization + Normalization
- Reads matrix into NumPy
- Generates histograms and box plots for top features
- Performs column-wise normalization and exports results

### — Data Cleaning + Column Selection
- Reads tab-delimited file using Pandas
- Fills missing values
- Caps outliers above a threshold (e.g., 2000)
- Selects columns containing `Context_` and exports cleaned subset

## Skills demonstrated
- Bioinformatics file formats: FASTA, GFF, BLAST XML
- Practical stats and ranking
- Clean preprocessing for omics matrices
- Visualization and reporting
- Reproducible project packaging and documentation

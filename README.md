# GWAS Manhattan & QQ Plot Generator

An R notebook that simulates GWAS summary statistics
and produces publication-ready Manhattan and QQ plots.

## What it does
- Simulates 5000 SNPs across 22 chromosomes
- Adds significant hits on chromosomes 3, 7 and 15
- Generates Manhattan plot with significance thresholds
- Generates QQ plot to assess p-value inflation
- Computes lambda GC genomic inflation factor

## Key results
- 10 genome-wide significant SNPs (p < 5e-8)
- Strongest signal on chromosome 7
- Lambda GC = 1.012 (no inflation)

## Packages used
- qqman — Manhattan and QQ plots
- dplyr — data manipulation

## Key concepts learned
- GWAS data structure (SNP, CHR, BP, P)
- Manhattan plot interpretation
- QQ plot interpretation
- Lambda GC genomic inflation factor
- Genome-wide significance threshold (5e-8)

## Author
K Vaishali
MSc Bioinformatics

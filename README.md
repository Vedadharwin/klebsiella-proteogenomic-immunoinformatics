# Proteogenomic and Immunoinformatics Analysis of *Klebsiella pneumoniae*

This repository documents a proteogenomic and immunoinformatics workflow for prioritizing potential vaccine-target and epitope candidates against *Klebsiella pneumoniae*.

The project integrates comparative genomics, antimicrobial resistance and virulence-associated analysis, proteomics-supported antigen prioritization, antigenicity screening, allergenicity assessment, epitope prediction, toxicity filtering, population coverage analysis, and peptide–HLA docking.

## Project Overview

*Klebsiella pneumoniae* is an important opportunistic bacterial pathogen associated with antimicrobial resistance and hospital-acquired infections. This project applies an integrated computational workflow to identify and prioritize candidate proteins and epitopes with potential relevance for vaccine-target exploration.

## Workflow Summary

The analysis includes:

1. Genome dataset collection and quality assessment
2. Species confirmation and genome filtering
3. Antimicrobial resistance and virulence-associated profiling
4. Pangenome-based protein screening
5. Proteomics-supported candidate prioritization
6. Human non-homology filtering
7. Protein antigenicity and allergenicity assessment
8. B-cell, MHC-I, and MHC-II epitope prediction
9. Toxicity filtering of selected epitopes
10. Population coverage analysis
11. Peptide-HLA docking using GalaxyPepDock
12. Structural visualization using PyMOL

## Repository Structure

- docs/ : Docking interpretation and analysis notes
- figures/docking/ : Peptide-HLA docking figures
- results/summary_tables/ : Final summary tables for selected analyses

## Tools Used

### Genomics and Comparative Analysis

- NCBI Datasets
- QUAST
- FastANI
- AMRFinderPlus
- Kleborate
- Panaroo
- IQ-TREE

### Immunoinformatics

- VaxiJen
- AllerTOP
- IEDB B-cell epitope prediction
- IEDB MHC-I and MHC-II binding prediction
- ToxinPred2
- IEDB population coverage analysis

### Structural Biology and Docking

- SWISS-MODEL
- PROCHECK
- PyMOL
- GalaxyPepDock

## Current Status

The computational workflow has been completed up to peptide-HLA docking. Final manuscript preparation and figure organization are in progress.

## Important Note

The candidates reported in this project are computationally prioritized. Further molecular dynamics simulation and experimental validation are required before biological or vaccine-related claims can be made.

## Author

R.M. Vedadharwin  
Aspiring Bioinformatician  
GitHub: @Vedadharwin  
Email: vedadharwin@gmail.com

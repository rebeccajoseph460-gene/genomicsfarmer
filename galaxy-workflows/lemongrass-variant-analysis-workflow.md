# Galaxy Workflow: Lemongrass Variant Analysis

## Overview

This workflow documents the bioinformatics pipeline used to identify and annotate genomic variants in Cymbopogon citratus (lemongrass) using the Galaxy platform.

The workflow was designed to identify genomic variants, predict their functional effects, and characterize candidate genes potentially associated with secondary metabolism and other important biological processes.

## Workflow Diagram

![Lemongrass Workflow](lemongrass%20workflow%20image.jpeg)

*Figure 1. Galaxy workflow used for sequence alignment, variant calling, functional annotation, and candidate gene identification in Cymbopogon citratus.*

## Input Data

- Whole-genome sequencing reads
- Cymbopogon citratus reference genome
- Gene annotation files
  
## Workflow Stages

### 1. Data Acquisition

- Import sequencing reads into Galaxy.
- Retrieve reference genome resources.
  
### 2. Reference Genome Preparation

- Prepare and index the reference genome for downstream analyses.

### 3. Sequence Alignment

**Tool:** BWA-MEM
- Align sequencing reads against the reference genome.
- Generate alignment files for variant detection.
  
### 4. Variant Calling

**Tool:** bcftools
- Detect SNPs and insertion/deletion variants.
- Generate VCF files containing genomic variants.

### 5. Variant Processing
- Sort and filter variant datasets.
- Prepare variants for downstream annotation.

### 6. Functional Annotation

**Tool:** SnpEff
- Predict variant effects.
- Classify variant impact levels.
- Identify coding and non-coding variants.

### 7. Functional Characterization

**Tool:** BLAST+
- Compare predicted sequences against reference databases.
- Assign putative biological functions.
  
### 8. Candidate Gene Identification

- Prioritize genes containing potentially important variants.
- Evaluate relevance to secondary metabolism and plant biological processes.

## Outputs

- VCF files
- Annotated variant datasets
- BLAST results
- Candidate gene lists
- Summary reports

## Key Skills Demonstrated

- Galaxy workflow development
- Whole-genome variant analysis
- Sequence alignment
- Variant calling
- Functional annotation
- BLAST-based characterization
- Candidate gene prioritization
- Bioinformatics data interpretation

## Future Improvements

- Transcriptome integration
- Metabolomic validation
- Additional lemongrass accessions
- Experimental verification of candidate variants

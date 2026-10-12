# Genomic Variant Analysis of Cymbopogon citratus (Lemongrass)

## Project Overview

This project investigated genetic variation in Cymbopogon citratus (lemongrass) ecotype PI 314907 using whole-genome sequencing data and bioinformatics approaches. The study aimed to identify coding-region variants, predict their functional effects, and determine whether they may influence genes associated with secondary metabolism and the production of bioactive compounds responsible for the plant's medicinal and aromatic properties.

## Objectives
- Identify genomic variants in Cymbopogon citratus.
- Detect protein-altering mutations, including SNPs and indels.
- Functionally annotate variant-containing genes.
- Identify candidate genes involved in secondary metabolite biosynthesis.
- Assess the potential impact of variants on protein function and metabolic pathways.
  
## Methods
### Data Source
- Whole-genome sequencing dataset from Cymbopogon citratus isolate 1 (PI 314907 root tissue).
- Sequence data retrieved from the NCBI Sequence Read Archive (SRA).
  
## Analysis Workflow
- Sequence retrieval through Galaxy.
- Alignment of paired-end reads to the Cymbopogon citratus reference genome using BWA-MEM.
- Variant calling using bcftools.
- Gene prediction using Augustus.
- Functional annotation using a custom SnpEff database.
- BLAST-based gene characterization.
- KEGG pathway investigation using KofamKOALA.
- Candidate gene prioritization based on predicted biological function.
  
## Tools Used
### Bioinformatics Platforms
- Galaxy Platform
- NCBI Sequence Read Archive (SRA)
- Microsoft Excel

## Analysis Tools
- BWA-MEM
- bcftools
- Augustus
- SnpEff
- BLAST+
- KofamKOALA
- SwissProt/nr Databases

## Results

Variant discovery identified coding-region polymorphisms across the lemongrass genome, with the majority classified as missense variants resulting in amino-acid substitutions. Most biologically relevant variants were predicted to have MODERATE functional impact.

## Major Findings
- 14,388 variant records were identified.
- Variants affected approximately 3,153 genes.
- 391 genes were supported by BLAST-based functional annotation.
- Most detected variants were missense mutations.
- Several variants occurred in genes associated with metabolism, stress response, defense, and cell wall formation.

## Notable Variants

### Acyl-CoA N-acyltransferase
- Gene: DXKC01000010.1.g4
- Mutation: c.158A>G
- Protein Change: p.Gln53Arg
- Impact: MODERATE

This variant represents a promising candidate due to the role of acyltransferases in plant metabolic pathways.

### Laccase-15-Like Protein
- Gene: DXKC01000032.1.g35
- Protein Changes:
- p.Glu373Gly
- p.Arg374Gln
- Impact: MODERATE

The presence of two adjacent amino-acid substitutions suggests possible effects on lignin biosynthesis, phenolic metabolism, and plant defense mechanisms.

## Candidate Genes

### Primary Candidates

### Acyl-CoA N-acyltransferase

- Potential role in metabolite biosynthesis.
- Missense variant p.Gln53Arg.

### Laccase-15-like Protein

- Associated with lignification and phenolic metabolism.
- Consecutive amino-acid substitutions detected.


### Secondary Candidates
- MYB transcription factors
- Neutral/Alkaline Invertase
- GDSL Esterase/Lipase
- Cytochrome P450 Family Proteins
- Flavin-containing Monooxygenases
  
## Lessons Learned

This study highlighted the challenges of working with non-model plant species, including limited genome annotation resources and the need for experimental validation to confirm predicted variant effects. Integrating variant data with functional annotation proved essential for identifying biologically meaningful candidate genes and prioritizing targets for future investigation.

## Skill Demonstarted

This project strengthened my skills in:

- Genome-scale variant analysis
- Galaxy workflow development
- Reference-based sequence alignment
- Variant calling and filtering
- Functional annotation using SnpEff
- BLAST-based gene characterization
- Candidate gene prioritization
- Scientific data interpretation and reporting

The study also highlighted the challenges of working with non-model plant species, including limited genome annotation resources and the need for experimental validation to confirm predicted variant effects. Furthermore, integrating variant data with functional annotation proved essential for identifying biologically meaningful candidate genes.

## Conclusion

This study successfully identified coding-region variants in Cymbopogon citratus and highlighted candidate genes potentially associated with secondary metabolism. The integration of variant analysis, functional annotation, and comparative sequence analysis provided valuable insights into the genetic basis of important biological processes in lemongrass.

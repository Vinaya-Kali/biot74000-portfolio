---
permalink: /toolkit/
title: "Bioinformatics Toolkit"
author_profile: true
---

<!--
  ============================================================================
  SECTION 2: BIOINFORMATICS TOOLKIT  (30 points)
  ============================================================================
  A curated, annotated catalogue of the tools, databases, file formats, and
  methods you worked with in this course. This is the POLISHED version of your
  Course Learning Log — not a copy-paste, but a professional re-write,
  organized by CATEGORY (not by unit).

  FOR EACH ENTRY, INCLUDE:
    - Tool / database name
    - 1–2 sentences describing one specific use example from the course
      that YOU performed
    - One note on a strength or a limitation

  SUGGESTED CATEGORIES (use the ones that fit your work; add or remove as needed):
    Sequence Analysis Tools · Databases & Data Retrieval ·
    Genome & Transcriptome Analysis · Protein Structure & Function ·
    Computational & Scripting Tools · Data Visualization

  Entries copied word-for-word from documentation will not receive full marks —
  use your own words. Quality and honesty matter more than the number of entries.

  HOW TO EDIT:
    - Replace the example entries below with your own.
    - Keep the same simple pattern: a "##" category heading, then one
      "###" heading per tool, then your notes underneath.
    - Delete these grey instruction notes before you submit.
  ============================================================================
-->

_A curated catalogue of the tools, databases, and methods I have worked with,
organized by what they are used for._
##Sequence Analysis Tools
###BLASTN
Course use: I used BLASTN to compare a selected nucleotide sequence against sequences in public databases. I evaluated the matches using E-value, query coverage, percentage identity, alignment length, and bit score.
Strength or limitation: BLASTN quickly identifies similar nucleotide sequences and possible homologues; however, high sequence similarity alone does not confirm that two sequences have the same biological function.

##FASTA Format
Course use: I retrieved DNA and protein sequences for a selected gene in FASTA format and used them as input for sequence analysis.
Strength or limitation: FASTA is simple, readable, and supported by most bioinformatics tools, but it contains limited metadata about the sequence.

##Databases and Data Retrieval
###NCBI GenBank
Course use: I used GenBank to retrieve the nucleotide sequence of a selected gene and to locate sequence information to support primer selection and downstream analysis.
Strength or limitation: GenBank is a large, freely accessible sequence repository, but the completeness and quality of submitted annotations can vary because not every record is manually reviewed.

###UniProt
Course use: I used UniProt to investigate the function of the NPR3 protein and identify its sequence, domains, and annotated functional regions.
Strength or limitation: UniProt provides detailed protein information and literature references. Reviewed Swiss-Prot records are highly reliable, while some unreviewed annotations are computational predictions that may require experimental confirmation.

###NCBI Gene Expression Omnibus (GEO)
Course use: I explored an RNA-seq dataset in NCBI GEO and reviewed its experimental design, sample metadata, treatment and control groups, and biological replicates.
Strength or limitation: GEO provides free access to a large collection of transcriptomic datasets, but the usefulness of a dataset depends on the quality and completeness of its metadata and experimental design.


##Genome and Transcriptome Analysis
###RNA Sequencing (RNA-seq)
Course use: I examined how RNA-seq data can be used to measure gene expression and compare transcriptional differences between treated and control samples.
Strength or limitation: RNA-seq can identify actively expressed genes and detect changes across experimental conditions. However, results can vary according to tissue type, sampling time, experimental conditions, and data-processing methods.

###Differential Expression Analysis with DESeq2
Course use: I interpreted DESeq2 differential expression results using log2 fold changes and adjusted p-values to identify significantly upregulated and downregulated genes.
Strength or limitation: DESeq2 uses normalization and statistical testing to help control false-positive findings, but results depend on data quality, normalization choices, sample size, and significance thresholds.

###g:Profiler
Course use: I explored g:Profiler to perform functional-enrichment analysis and determine which biological processes, molecular functions, and cellular components were overrepresented in a list of differentially expressed genes.
Strength or limitation: g:Profiler helps interpret the biological meaning of a gene list, but enrichment results show statistical associations and do not establish biological causation.

##Protein Structure and Function

###AlphaFold and pLDDT Scores
Course use: I explored an AlphaFold prediction for the NPR3 protein and interpreted pLDDT confidence scores to distinguish confidently predicted regions from flexible, disordered, or uncertain regions.
Strength or limitation: AlphaFold provides useful structural models for proteins without experimentally determined structures, but low-confidence regions must be interpreted carefully and should not be treated as confirmed structures.

###RCSB Protein Data Bank
Course use: I used the RCSB Protein Data Bank to locate an experimentally determined protein structure and compare it with an AlphaFold prediction, examining similarities and differences between the experimental and predicted models.
Strength or limitation: RCSB PDB provides experimentally determined three-dimensional structures and information about the methods used to obtain them. However, many proteins have no complete experimental structure available.

###Variant Mapping
Course use: I examined how amino acid variants can be mapped onto a protein structure and evaluated how changes at conserved residues could affect protein folding or biological function.
Strength or limitation: Variant mapping is useful for studying disease-associated mutations and supporting protein-engineering decisions, but predicted effects require structural, functional, and experimental evidence.

##Computational and Portfolio Tools
###GitHub and GitHub Pages
Course use: I created a GitHub repository for my bioinformatics portfolio and published it as a GitHub Pages website. I used the repository to organize and present course activities and bioinformatics learning outcomes.
Strength or limitation: GitHub provides version control, organized file management, and free website hosting through GitHub Pages. However, publishing and updating the website require an accurate repository structure and configuration.

##Data Visualization
###Volcano Plots
Course use: I interpreted volcano plots to identify genes showing both a large change in expression and statistically significant results.
Strength or limitation: Volcano plots quickly highlight potentially important differentially expressed genes, but the results depend on the selected fold-change and significance thresholds.

###Heatmaps
Course use: I interpreted heatmaps to identify gene expression patterns and to compare relationships among experimental samples or groups.
Strength or limitation: Heatmaps make clusters and expression patterns easier to recognize, but their appearance can be influenced by scaling, gene selection, and clustering methods.

---

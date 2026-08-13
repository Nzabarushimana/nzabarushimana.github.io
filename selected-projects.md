---
layout: default
title: Projects
description: Selected computational biology projects in metagenomics, multi-omics, biomarker modeling, method development, and translational disease research.
permalink: /selected-projects/
---

# Projects

My work combines biological context, rigorous quantitative analysis, and reproducible computing. The projects below illustrate how I approach biomarker discovery, computational method development, multi-omic integration, and translational interpretation.

<a id="cdi"></a>

## Clinical Biomarker Modeling for *Clostridioides difficile* Infection

**Challenge**  
Determine whether the functional and taxonomic composition of the gut microbiome could distinguish active *C. difficile* infection from other gastrointestinal conditions and from antibiotic-associated microbiome disruption.

**Approach**  
Integrated clinical fecal metagenomic data from 10 published studies. Developed a hybrid species/function profiling strategy, evaluated logistic-regression and LASSO models, assessed antibiotic exposure as a confounder, and used both fivefold and leave-one-study-out validation.

**Results**  
The full logistic-regression model achieved an average AUC of 0.919 in fivefold cross-validation and 0.912 in leave-one-study-out validation for distinguishing CDI-positive from CDI-negative samples. A LASSO model selected a compact 21-species signature and achieved average AUCs of 0.951 and 0.947 in two primary fivefold validation comparisons. An interpretable log-odds score was also used to evaluate microbiome recovery following successful fecal microbiota transplantation.

**Why it matters**  
The project demonstrates how functionally informed microbiome profiles and interpretable modeling can support disease classification while explicitly examining clinical confounding and cross-study generalizability.

**Methods:** Metagenomics &middot; Functional profiling &middot; Logistic regression &middot; LASSO &middot; Cross-validation &middot; Confounder analysis

[Read the publication](https://doi.org/10.1080/19490976.2022.2135963) &nbsp;&middot;&nbsp; [Free full text](https://pmc.ncbi.nlm.nih.gov/articles/PMC9621045/)

<a id="waafle"></a>

## WAAFLE: Detecting Lateral Gene Transfer in Metagenomes

**Challenge**  
Lateral gene transfer is an important driver of microbial genome evolution, but detecting transfer events directly from complex community metagenomes is difficult when isolate genomes are unavailable.

**Approach**  
Co-developed WAAFLE&mdash;Workflow to Annotate Assemblies and Find LGT Events&mdash;a computational method that integrates sequence homology, gene organization, and taxonomic provenance to identify metagenomic contigs best explained by pairs of microbial clades rather than a single clade.

**Contribution**  
Contributed to problem formulation, algorithm and workflow development, validation, biological interpretation, and scientific communication as a co-lead author.

**Outcome**  
The work produced an open-source, installable workflow, documentation, tutorial materials, and a co-lead-author publication in *Nature Microbiology*.

**Methods:** Algorithm development &middot; Metagenomic assembly analysis &middot; Sequence homology &middot; Taxonomic inference &middot; Validation &middot; Reproducible software

[Read the publication](https://doi.org/10.1038/s41564-024-01881-w) &nbsp;&middot;&nbsp; [Documentation](https://huttenhower.sph.harvard.edu/waafle/) &nbsp;&middot;&nbsp; [Source code](https://github.com/biobakery/waafle)

<a id="multi-omics"></a>

## Transkingdom Multi-Omics in MASLD

**Challenge**  
Characterize microbial, transcriptional, viral, metabolic, and clinical features associated with metabolic dysfunction-associated steatotic liver disease, including differences between lean and non-lean disease.

**Approach**  
Contributed to a high-resolution multi-omic study of 211 MASLD cases and 502 controls that integrated stool metagenomes, metatranscriptomes, metabolomes, viral profiles, and clinical variables.

**Results**  
The study identified transkingdom dysbiosis involving bacterial and viral taxa, disease-associated microbial transcriptional and metabolic shifts, and coordinated changes involving polyamines, acylcarnitines, secondary bile acids, and oral-typical microbes.

**Why it matters**  
The work provides an integrated molecular resource for studying MASLD biology and illustrates how multiple data modalities can reveal relationships that are not visible from taxonomic profiles alone.

**Methods:** Metagenomics &middot; Metatranscriptomics &middot; Metabolomics &middot; Virome analysis &middot; Multi-omic integration &middot; Clinical-cohort modeling

[Read the publication](https://doi.org/10.1038/s42255-025-01318-6) &nbsp;&middot;&nbsp; [Analysis code](https://github.com/biobakery/MASLD)

## Microbial and Metabolic Signatures in Microscopic Colitis

**Challenge**  
Identify microbiome and metabolome features associated with microscopic colitis, a chronic inflammatory disease for which validated non-invasive biomarkers remain limited.

**Approach**  
Contributed to a study of 683 participants&mdash;including active microscopic colitis, chronic-diarrhea comparators, and age- and sex-matched controls&mdash;using whole-genome shotgun metagenomics, mass-spectrometry-based metabolomics, longitudinal analysis, and multivariable modeling.

**Results**  
The study identified distinct microbial and metabolic signatures, including disease-associated oral-typical species, depletion of potentially anti-inflammatory species, and coordinated alterations in pro-inflammatory lipid metabolites. Longitudinal analyses evaluated shifts between active disease and remission.

**Why it matters**  
The results support the development of non-invasive biomarker hypotheses and provide mechanistic leads connecting microbial composition, metabolic pathways, and inflammatory disease activity.

**Methods:** Shotgun metagenomics &middot; Metabolomics &middot; Longitudinal analysis &middot; Multivariable modeling &middot; Microbe&ndash;metabolite integration

[Read the publication](https://doi.org/10.1038/s41467-025-59566-9) &nbsp;&middot;&nbsp; [Analysis code](https://github.com/albertsyc/Association-of-Distinct-Microbial-and-Metabolic-Signatures-with-Microscopic-Colitis)

## Earlier Experimental Research

Before focusing primarily on computational biology, I led and contributed to experimental studies of ionizing-radiation effects, epigenetic regulation, inflammatory signaling, lung biology, cancer risk, and disease mechanisms. This work included study design, molecular assays, sample handling, data interpretation, and publication. It continues to inform how I evaluate assay limitations and biological plausibility in computational research.

[Related publication](https://pmc.ncbi.nlm.nih.gov/articles/PMC4641818/) &nbsp;&middot;&nbsp; [View all publications]({{ '/publications/' | relative_url }})

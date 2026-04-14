---
layout: post
title:  "DOMINO Workshop on F3M Food Microbiome Metabolic Modules at CSIC Madrid"
date:   2026-04-14 9:50:07
categories: workshop
members_tag: Julien Tap, Stéphane Chaillou, Nacer Mohellibi
projects_tag: Domino
description: "DOMINO Workshop on F3M"
image: /img/2026_f3m_workshop_domino.png
published: true
#canonical_url: https://www.csrhymes.com/development/2018/05/28/why-use-a-static-site-generator.html
---

The 14th of April 2026, teams from INRAE (MICALIS & MaIAGE) organised a hands-on
workshop in Madrid at CSIC, focused on the F3M ecosystem (Food Microbiomes
Metabolic Modules) and its associated tools for functional microbiome analysis.




This workshop was organised in the framework of the Domino project, with a
strong focus on enabling partners to manipulate the 
[F3M tool suite](https://fme.micalis.fr/article/2025/11/06/food-microbiome-metabolic-modules-f3m/)
for microbiome data integration, gene catalog construction, and functional
interpretation.

The morning sessions introduced the conceptual foundations of the
[F3M curated database and the associated tools](https://fme_team.pages-forge.inrae.fr/F3M_Builder_Tutorial/Slides/DOMINO_3AM_F3M_workshop.pdf).

![](/img/2026_f3m_workshop_participants_domino.png)

Participants were then guided through
practical use of the f3mr R package, focusing on data aggregation at both
taxonomic and functional levels, normalization, and differential analysis
workflows (notably using DESeq2), followed by integration into phyloseq for
downstream functional mining.

See the tutorial [here](https://fme_team.pages-forge.inrae.fr/F3M_Builder_Tutorial/README.html)

After a working lunch, the afternoon sessions shifted toward more advanced
tasks. Participants explored how to map metagenomic reads onto an existing
F3M-inferred gene catalog, and how to construct a custom gene catalog from a
defined list of microbial species.
The tutorial, developed by [Mohellibi Nacer](/team/nacer-mohellibi/), 
[Stéphane Chaillou](/team/stephane-chaillou/), and Valentin Loux, provided a complete
pipeline:

- Mapping reads to a reference gene catalog using f3m_builder map
- Building gene catalogs from pangenomic inputs using f3m_builder build_catalog
- Exploring outputs in R using [f3mr](https://fme_team.pages-forge.inrae.fr/f3mr/)

The training relied on the 
[Migale HPC infrastructure](https://migale.inrae.fr/), 
with both interactive (qlogin) and
batch (qsub) execution modes, ensuring scalability and reproducibility of
analyses.

A key outcome of the workshop is that participants are now able to move across
the full workflow: from raw sequencing reads to structured functional profiles
linked to metabolic modules. This enables a tighter integration between
microbial composition and functional potential in food microbiome datasets. The
session ended with discussions on applications, including the design of
microbial consortia and the exploitation of F3M modules for hypothesis-driven
microbiome engineering.

Thank to CSIC for hosting.

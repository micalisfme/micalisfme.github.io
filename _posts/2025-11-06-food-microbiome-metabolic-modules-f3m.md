---
layout: post
title:  "New tool suite - Food Microbiome Metabolic Modules (F3M)"
date:   2025-11-06 18:50:07
categories: article
members_tag: Julien Tap, Nacer Mohellibi, Colin Tinsley, Stéphane Chaillou
description: "Food Microbiome Metabolic Modules (F3M), a tool suite for functional profiling of food microbiomes"
image: /img/F3M_modules.gif
published: true
#canonical_url: https://www.csrhymes.com/development/2018/05/28/why-use-a-static-site-generator.html
---

The FME team has published a new preprint in *Open Research Europe* entitled  
**“Food Microbiome Metabolic Modules (F3M): a tool suite for functional profiling of food microbiomes.”**  
[Read the article](https://open-research-europe.ec.europa.eu/articles/5-324)

Understanding microbial interactions within food ecosystems is essential for improving the quality, safety, and health properties of fermented foods. However, analyzing these interactions at the functional and metabolic levels remains technically challenging.To address this gap, the FME team developed **F3M**, an open-source suite designed specifically for the metatranscriptomic analysis of food microbiomes.  


![](/img/F3M_modules.gif)

<figure>
  <img src="{{site.url}}/img/F3M_modules.gif" alt="Overview of different classes among the F3M main functional modules allowing the linkage of the major functional processes in microbial interactions."/>
  <figcaption>Overview of different classes among the F3M main functional modules allowing the linkage of the major functional processes in microbial interactions:: the modules for metabolism (illustrated by the pathways within the two bacterial cells), redox processes (central oxido-reduction mechanisms between the two cells), and uptake processes (various transporters in the cell membrane of the two cells).</figcaption>
</figure>


The F3M suite includes:  
- A **curated database** of nearly 2,000 functional genes representing key fermentative reactions  
- The **F3M Builder**, a workflow for constructing annotated gene catalogs and mapping sequencing data  
- The **f3mr R package**, which enables aggregation and analysis of gene expression data across taxonomic and functional levels  

Together, these tools provide a coherent framework for exploring metabolic interactions within food microbiomes and for identifying functional signatures associated with fermentation processes.  

The article[^1], authored by **Julien Tap, Nacer Mohellibi, Colin Tinsley, Valentin Loux, and Stéphane Chaillou**, describes the conceptual framework, design, and open-access resources of F3M.  

**Access the resources:**  
- [F3M database](https://doi.org/10.57745/9VKS65)  
- [f3mr R package](https://forge.inrae.fr/fme_team/f3mr)  
- [F3M builder](https://forge.inrae.fr/fme_team/f3m_builder)

[^1]: Tap et al. [*Food Microbiome Metabolic Modules (F3M), a tool suite for functional profiling of food microbiomes](https://open-research-europe.ec.europa.eu/articles/5-324).  Open Research Europe. 2025


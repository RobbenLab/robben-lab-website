---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

<!-- Project 1 -->

{% capture text %}

scRNA-seq analysis of T-cells extracted from diabetic NOD mice revealed interesting indicators of T-cell dysregulation associated with development of the disease. This included suppression of cytotoxic CD8+ T-cells on infiltration into the pancreas associated with specific TCR clones, and the remarkeable increased rate of Double Negative (DN) T-cells among circulating and infiltrating T lymphocytes. The objective or our research is two fold 1. Develop molecular and computational tools to identify epitopes for suppressed and unsuppressed cytotoxic T-cells and 2. Determine the mechanism of action for the development of circulating DN T-cells and their effect on disease progression.  

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/nodDN.png"
  title="Dysregulation of T-cells in inflammatory diabetes"
  text=text
%}

{% include section.html %}

<!-- Project 2 -->

{% capture text %}

The inclusion of machine learning algorithms in the prediction of nucleic acid and protein biology holds great promise for groundbreaking discovery. Our goal is to build the foundation for the use of these tools in genomic research. We previously demonstrated that machine learning algorithms can benefit annotation of microbial genes to discover previously undiscovered pathways. Our goal is to develop better algorithms that can aid genomic researchers in gene discovery. The use of machine learning to replace wet lab experiments or generate more data than wet lab experiments is also a topic of great interest. New structural biology algorithms such as alphafold present the opportunity to predict protein-protein interactions in-silico. Developing these algorithms to be faster and more efficient will allow us to evaluate millions of potential interactions more efficiently than can be done with Y2H or PPI experiments. These faster screening algorithms can then be applied to discovering antigen specific antibodies in-silico which can be used for discovery of new immunotherapuetics.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/62277caa7b7ddd67e5c7a0ad_Fig 2.gif"
  title="Machine-learning models for genomics and structural biology"
  text=text
%}

{% include section.html %}

<!-- Project 3 -->

{% capture text %}

Single cell and spatial omics technologies offer a new way to understand the biology of tumor development and immune cell interaction. Due the immaturity of this technology the methods to generate this data is much more developed than the methods for analysis. Topics that still need development are clustering algorithms and cell type identification, low sequencing depth and sampling error, and the recognition of cell-cell interactions/signaling events. In our lab we use computer vision algorithms which include vision transformers, resnets, and unsupervised learning to address these opportunities. A focus of our research is establishing a universal method of gene expression modeling for the different technologies of spatial transcriptomics that will standardize resolution to the single-cell level. 

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/Emory-Mouse-Liver.jpg"
  title="Computational methods for the analysis of spatial and single-cell sequencing of the tumor microenvironment"
  text=text
%}

{% include section.html %}

## Packages

Coming soon...

<!-- {% include list.html component="card" data="projects" filters="group: featured" %} -->

{% include section.html %}

## Funding Sources

{%
  include figure.html
  image="images/Funding/ACES.PNG"
%}

{% include section.html %}
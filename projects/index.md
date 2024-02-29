---
title: Projects
nav:
  order: 2
  tooltip: Current projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

<!-- Project 1 -->

{% capture text %}

Type-1 Diabetes is an inflammatory autoimmune disease that develops during childhood where immune dysregulation leads to Beta-cell destruction and a loss of the bodies ability to regulate insulin production. This disease affects millions worldwide and is curiosly more common in highly modernized western countries. To explore this disease we previously conducted single cell RNA-seq and TCR-seq in the translation NOD mouse model and found interesting results concerning T-cell regulation. Most strikingly, Double Negative (DN) T-cells, represent ~1/3 of active effector T-cell populations and recieve increased signaling for exhaustion in diabetic mice. On top of this, a population of clonal specific CD8+ T-cells show abnormal exhaustion regulation from other CD8+ T-cells in the diabetic mouse, where apparently exhausted cytotoxic T-cells will leave the pancreas and resume expression of granzymes and perforin. Our lab is engaged in further research to 1) Identify the origin of DN T-cells in the NOD mouse and it's role in pathogenesis 2) Identify the targets of misregulated TCR sequences and 3) Observe the spatial dynamics of T-cell interaction within the pancreas. 

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/NODdisc.png"
  title="Dysregulation of T-cells in inflammatory diabetes"
  text=text
%}

{% include section.html %}

<!-- Project 2 -->

{% capture text %}

Racial and genetic bias towards the development of cancer is a major factor that disproportionally impacts at-risk populations in this country. Black American populations are at higher risk of developing and dying from prostate and colorectal cancer, while Asian American populations are the only which have seen increases in breast cancer mortality in the last decade. Interestingly, native populations of genetically similar ethnic groups do not experience the same incidence or mortality of disease with their genetic matches in the US. This perplexing nature of unequal bias in cancer development has gone long unresearched by the wider scientific community due to geographical barriers in patient groups, but has become more possible now thanks to the wide abundance of publically available sequencing data. Using this data, we can conduct international investigation into patients suffering from similar cancer and observe how the combined effect of genotype and environment result in the different pathology among individuals. Through this research we hope to identify biomarkers or risk factors unique to individual ethnic groups to improve health equity and cancer survival. 

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/cancerimage.png"
  title="Exploring environmental effects on cancer progression through international sequencing data"
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

---

carousels:
  - images: 
    - image: images/Gallery/ERML.jpg
    - image: images/Gallery/IGB-mainpage.jpg
    - image: images/Gallery/NCSA-petascale-computing-facility-university-of-illinois-new1-copy--2000.jpg
    - image: images/Gallery/210714-submitted.png

---

# Illinois Laboratory for Animal Machine-learning and Bioinformatics

The goal of the Robben lab is to develop the next generation of multi-omic sequencing technologies to investigate immune cell dysfunction in cancer and autoimmune disease using animal models. The future of high-throughput sequencing combines transcriptomics, proteomics, genomics and imaging into techniques like single cell RNA-seq and spatial transcriptomics. For the analysis of this data we need new computational methods utilizing machine learning algorithms that can identify patterns of cell interactions and differentiation.  
---  
<!---**Currently looking for highly self-motivated graduate and undergraduate students who want interdisciplinary research experience! See the "Join Us" tab for more details.** --->

{% include section.html %}


{% include carousel.html height="50" unit="%" duration="7" number="1" %}

{% include section.html %}

## Highlights

{% capture text %}

Recently published articles and conference papers by members of the Robben Lab.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/nodDN.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Active projects in the pipeline and links to computational packages developed in the lab.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/thumbnails/Emory-Mouse-Liver.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Meet the highly talented individuals that make up the best team for doing interdisciplinary research.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Gallery/ERML.jpg"
  link="team"
  title="Our Team"
  text=text
%}

---
---

# Translating genetic data into disease biology and patient care

The Strober lab (PI: Ben) is a computational group focused on developing statistical and machine learning tools applied to human genetic and genomic data with the goals of elucidating disease biology and advancing genomically-informed precision medicine. We are particularly interested in modeling the regulatory cascade from DNA through molecular phenotypes, such as transcript and protein levels, to  diseases and traits, in order to illuminate mechanisms that drive disease. We also aim to integrate multimodal omics with the rich clinical data to refine diagnoses and guide precision-medicine interventions.


Our lab is part of the [Computational Health Informatics Program](https://www.chip.org/) at Boston Children's Hospital, a teaching affiliate of Harvard Medical School.


<div style="text-align: center; margin-top: 40px;">
  <a href="https://chip.org" target="_blank"><img src="images/chip-logo.png" alt="CHIP" style="height:85px; margin:0 65px;"></a>
  <a href="https://www.childrenshospital.org/" target="_blank"><img src="images/BCH2.svg" alt="Boston Children's Hospital" style="height:85px; margin:0 65px;"></a>
  <a href="https://hms.harvard.edu/" target="_blank"><img src="images/HMS.png" alt="Harvard Medical School" style="height:85px; margin:0 65px;"></a>
</div>


{% include section.html %}

## Highlights

{% capture text %}

Check out recent publications from the lab.

{%
  include button.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include feature.html
  image="images/papers_tgfm3.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are actively hiring to build our team! We welcome scientists at all levels and all backgrounds.

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
  image="images/lab_space.jpg"
  link="team"
  title="Our Team"
  text=text
%}

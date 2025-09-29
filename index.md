---
---

# BennyStrobes's Website

The Strober lab is a computational group focused on developing statistical and machine learning tools applied to genomic data to elucidate disease biology and advance genomically-informed precision medicine. 

Our lab is part of the [Computational Health Informatics Program](https://www.chip.org/) at Boston Children's Hospital, a teaching affiliate of Harvard Medical School.

<div style="text-align: center; margin-top: 40px;">
  <a href="https://chip.org" target="_blank">
    <img src="images/chip-logo.png" alt="CHIP" height="60">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.childrenshospital.org/" target="_blank">
    <img src="images/BCH.svg" alt="Boston Children's Hospital" height="60">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://hms.harvard.edu/" target="_blank">
    <img src="images/framed_hms_logo.png" alt="Harvard Medical School" height="60">
  </a>
</div>


{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
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

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

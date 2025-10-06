---
title: Research
nav:
  order: 1
  tooltip: Research overview
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research overview

{% include section.html %}

**Modeling the context-specificity of genetic regulation of gene expresssion**

{% capture col1 %}

Genetic variants significantly associated with gene expression are known as expression quantitative trait loci (eQTLs). eQTLs are a widely used approach to study the genetic regulation of gene expression and can also be used to infer the biological mechanisms and causal genes underlying disease-associated genetic variants. Dr. Strober has led several projects characterizing how eQTLs vary across tissues and cellular contexts. This includes work demonstrating that eQTLs are highly dynamic statistical associations that change continuously during process such as cellular differentiation ([Strober*, Elorbany*, Rhodes* et al. Science 2019](https://pubmed.ncbi.nlm.nih.gov/31249060/)). He also developed a probabilistic model, SURGE, to identify highly context-specific eQTLs from single-cell RNA sequencing using latent-factor models ([Strober et al. Genome Biology 2024](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03152-z)). Together, these studies demonstrated that genetic regulation of gene expression is highly dynamic and depends on cellular context. 

{% endcapture %}

{% capture col2 %}

{% include figure.html image="images/papers_surge2.jpeg" caption="SURGE model overview" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}
**Elucidating disease biology through integration of genetic association studies and functional genomic data**

{% capture col1 %}

Genome-wide association studies (GWAS) have identified hundreds of thousands of genetic variants associated with human disease. Most of these variants lie in non-coding regions of the genome and are generally thought to influence disease risk by regulating the expression of nearby genes. Yet despite extensive efforts, most disease-associated genetic variants remain functionally uncharacterized, with the causal gene unknown in most cases. This has emerged as a major limitation in human genetics, slowing progress toward biological insight and gene-targeted strategy. **A major goal of the lab is develop integrative statistical approaches to connect variant-to-gene regulation with diseae** and infer biological mechanisms underlying disease-associated genetic variants. This work will relies on integration of GWAS data with diverse variant-to-gene linking strategies from functional genomic data (QTLs, CRISPR-based perturbations, enhancer gene links from single-cell multiome assays, chromatin contact maps, etc). 

We recently developed Tissue-Gene Fine-Mapping (TGFM), a statistical method to uncover the functional mechanisms underlying disease-associated variants by integrating multi-tissue eQTL data with GWAS data ([Strober et al. Nature Genetics 2025](https://pubmed.ncbi.nlm.nih.gov/37961337/)).TGFM exploits variation in eQTL effects across tissues to pinpoint both the causal gene and its tissue of action at each GWAS locus.

{% endcapture %}

{% capture col2 %}

{% include figure.html image="images/papers_tgfm6.jpg" caption="TGFM identifies OVOL1 in lymphocytes as a causal-gene-tissue pair underlying an Eczema disease locus" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}



{% include section.html %}
**Advancing genomically-informed precision medicine for rare diseases**

{% include section.html %}
**Inferring variant-to-gene links and disease genes using deep learning sequence-to-expression models**

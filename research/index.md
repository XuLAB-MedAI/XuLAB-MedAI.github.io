---
title: Research
nav:
  order: 1
  tooltip: medical image analysis, computational pathology, and more
---

# {% include icon.html icon="fa-solid fa-dna" %}Research

{% capture content %}
{%
  include figure.html
  image="images/research1.PNG"
  caption="The pipeline for multiple instance learning"
  width="410px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

Whole slide images (WSIs) contain rich information for cancer diagnosis, biomarker expression prediction, and patient survival outcome estimation. However, analyzing WSIs remains challenging due to their large size and the scarcity of expert annotations. Multiple instance learning (MIL) models have emerged as the dominant approach for WSI classification. Our lab is dedicated to developing novel MIL models by leveraging foundation models, graph-based methods, and attention mechanisms to advance WSI-based diagnostic tasks.
{% include float.html clear=true %}

{% capture content %}
{%
  include figure.html
  image="images/kd.PNG"
  caption="Knowledge distillation example for molecular predictions"
  width="600px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}
Multimodal learning, which integrates radiological images (e.g., CT, MRI), H&E-stained slides, and genomic data, enhances the prediction of molecular biomarker status, patient treatment responses, and survival outcomes. However, the simultaneous acquisition of genomic, pathological, and radiological data is often limited by cost and technical constraints. To overcome this challenge, our lab focuses on developing novel knowledge-distillation models that effectively integrate multimodal data during training while dynamically adapting to available data during inference.

{% include float.html clear=true %}

{% capture content %}
{%
  include figure.html
  image="images/edQTL_enrichment.png"
  caption="edQTLs mediate heritability of inflammatory diseases "
  width="375px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

During Dr. Li's postdoctoral training, he turned to human genetics for answers to these questions. He discovered that RNA editing quantitative trait loci (edQTLs) are strongly enriched in GWAS signals of common inflammatory diseases, even more than gene expression QTL and RNA splicing QTL. Furthermore, he showed that GWAS risk alleles, by each reducing editing level of their nearby immunogenic dsRNAs, can collectively elicit MDA5-dependent dsRNA sensing and subsequent chronic inflammation in a wide range of autoimmune and inflammatory diseases ([Li et al., Nature 2022](https://www.nature.com/articles/s41586-022-05052-x)). These findings, based on well-established mechanism and human genetic evidence, show that insufficient RNA editing is a major risk factor underlying inflammatory diseases.
{% include float.html clear=true %}

{% capture content %}
{%
  include figure.html
  image="images/dsRNA_burden.png"
  caption="Personalized dsRNA burden predicts individual's disease risk"
  width="800px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

Our lab's research goal is to advance basic understanding of dsRNA editing and sensing to develop better tools for diagnosis and treatment of inflammatory disease patients. Specifically, we ask three questions:

  - How do self dsRNAs evade innate immune sensing?
  - How do disease associated genetic variants affect dsRNA editing and sensing?
  - Which disease relevant cells are the trigger of immune response due to unwanted RNA sensing?

We employ an integrated approach including both computational and experimental tools to address basic questions in dsRNA editing and sensing. By doing so, we aim to bring new insights into autoimmunity and RNA therapeutics.

{% include float.html clear=true %}

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

<!-- ## Projects

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

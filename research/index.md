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
  caption="Knowledge distillation example for molecular biomarker predictions"
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
  image="images/gan.png"
  caption="Generating virtual IHC slide from H&E slide"
  width="375px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=false
%}

In clinical applications, generating medical images such as IHC slides is costly and time-consuming. Additionally, acquiring multimodal medical images for analysis is challenging, as missing modalities frequently occur across different patients and clinical centers. To address these limitations, our lab focuses on developing novel generative AI models by leveraging GANs, diffusion models, and contrastive learning strategies for biomedical applications.
{% include float.html clear=true %}

{% capture content %}
{%
  include figure.html
  image="images/multimodal.PNG"
  caption="Multimodal learning for CT imaging and clinical data."
  width="800px"
%}
{% endcapture %}

{%
  include float.html
  content=content
  flip=true
%}

Cancer diagnosis relys on multi-modal, multi-time point, multi-scale data information. To construct advanced AI models to assist in cancer diagnosis and treatment, our lab focuses on developing novel multi-modal learning AI models. Specifically, we have devoted our efforts to the following tasks:

  - How to effectively intregrate MRI and pathology slides for cervical cancer diagnosis and prognosis?
  - How to effectively integrate CT imaging and clinical variables for colorectal cancer treatment response prediction?
  - How to effectively integrate pathology slides and genomic data for cancer patient survival risk prediction?

We employ multimodal learning methods, cross-attention mechanisms, diffusion models, domain adaptations, feature decoupling and many other techniques in this topic.

{% include float.html clear=true %}

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

<!-- ## Projects

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

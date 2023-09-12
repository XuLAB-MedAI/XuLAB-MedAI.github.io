---
title: Research
nav:
  order: 1
  tooltip: dsRNA, RNA editing, ADAR, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include figure.html
  image="images/RNA_editing.png"
  caption="A-to-I RNA editing: ADAR converts adenosine to inosine in double-stranded RNA"
  width="600px"
%}

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filters="group: " style="small" %}

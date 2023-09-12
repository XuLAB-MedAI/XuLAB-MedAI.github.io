---
---

# Welcome to the Li lab!

We are the Li Lab in the [department of genetics](https://genetics.med.upenn.edu/) at the [University of Pennsylvania Perelman School of Medicine](https://www.med.upenn.edu/). 

Our lab study the genetic basis of RNA recognition and the diseases caused by dysregulated RNA sensing. We use an integrated approach to  Read more [here!](research)

{% include section.html %}

## Highlights

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="research"
  text="Browse our research"
  icon="fa-solid fa-arrow-right"
  flip=false
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/RNA-7.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=false
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/dsRNA_tree.png"
  link="research"
  title="Our Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=false
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team2.jpeg"
  link="team"
  title="Our Team"
  text=text
%}

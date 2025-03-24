---
---

# {% include icon.html icon="fa-solid fa-building-columns" %}Welcome to the Xu lab!

We are the Xu Lab in the [Faculty of Medicine](https://med.dlut.edu.cn/) at the [Dalian University of Technology](https://www.dlut.edu.cn/).

Our lab focuses on artificial intelligence in biomedical imaging, with a particular emphasis on Medical AI and pathology computing. Read more [here!](research)

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
  image="images/bg1.png"
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
  image="images/bg2.png"
  link="publications"
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
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=text
%}

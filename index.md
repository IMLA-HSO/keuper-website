---
title: Home
---

{% include section.html %}

# Janis' research Pages
Private research pages by ***Janis Keuper***. I work on the intersections of **Machine Learning (ML), Computer Vision (CV), and ML/CV for Geophysics**.

{:.center}
### Latest Highlights

{%
  include card.html
  image="https://jmlr.org/tmlr/img/tmlr.jpg"
  link=""
  title="TMLR"
  subtitle="journal paper"
  style="small"
%}
{%
  include card.html
  image="images/cvpr_23.png"
  link=""
  title="CVPR 23"
  subtitle="workshop paper"
  style="small"
%}

{%
  include card.html
  image="images/neurips_22.png"
  link="https://www.keuper-labs.org/research/neurips22.html"
  title="NeurIPS 22"
  subtitle="paper"
  style="small"
%}

{%
  include card.html
  image="images/eccv_22.png"
  link=""
  title="ECCV 22"
  subtitle="paper"
  style="small"
%}


{% include section.html %}


{% capture text %}
Latest papers on Computer Vision, Machine Learning and HPC topics...

{%
  include link.html
  link="research"
  text="Publications"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/paper.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Research projects and funding...

{%
  include link.html
  link="tools"
  text="Projects"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/projects.jpg"
  link="resources"
  title="Our Projects"
  flip=true
  text=text
%}

{% capture text %}
Team... 

{%
  include link.html
  link="team"
  text="Meet our teams"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/eccv.jpg"
  link="team"
  title="PhD Students"
  text=text
%}

{:.center}

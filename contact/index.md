---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

This private website aggregates research. Please refer to the official university site linked below for contact details ... 


{:.center}



{% include section.html %}


{% capture col1 %}
{%
  include figure.html
  image="images/RGB_IMLA_RGB_Farbe.jpg"
  link="https://imla.hs-offenburg.de/"
  height="80px"
  caption="Institute for Machine Learning and Analytics"
%}
{%
  include link.html
  link="https://imla.hs-offenburg.de/"
  text="visit group pages at Offenburg University"
  icon="fas fa-arrow-right"
  flip=true
%}
{% endcapture %}
{% capture col2 %}
{% endcapture %}

{% include two-col.html col1=col1 col2=col2 %}

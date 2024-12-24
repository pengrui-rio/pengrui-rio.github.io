---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Dr. Peng LU

Adaptive Robotic Controls Lab (ArcLab)

LG02, Haking Wong Building

University of Hong Kong (HKU)

ArcLab is located near Exit A2 of HKU station which is easily accessible.

{%
  include button.html
  type="email"
  text="lupeng@hku.hk"
  link="lupeng@hku.hk"
%}
{%
  include button.html
  type="phone"
  text="+852-3910 2548"
  link="+852-3910 2548"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/HKU+Station/@22.283061,114.134265,16z/data=!4m6!3m5!1s0x3403ff84558ca189:0x7dea16aa57d61c84!8m2!3d22.283984!4d114.135042!16zL20vMDZxZDRk?hl=en&entry=ttu&g_ep=EgoyMDI0MTIxMS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Google map"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Baidu map"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

<!-- {% include section.html dark=true %} -->



<!-- {% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %} -->

<!-- {% include cols.html col1=col1 col2=col2 col3=col3 %} -->

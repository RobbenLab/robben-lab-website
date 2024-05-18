---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please contact our lab for material or data requests or inquiries about collaboration.

{%
  include button.html
  type="email"
  text="Email"
  link="robben@illinois.edu"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="ERML 211"
  link="https://www.google.com/maps/place/Edward+R.+Madigan+Labratory/@40.1030506,-88.2243116,17z/data=!3m1!5s0x880cd716fc13fabf:0xcf6a02397531e490!4m6!3m5!1s0x880cd716fc8f7a7d:0x7ad8cd794e3df64d!8m2!3d40.1037837!4d-88.223828!16s%2Fg%2F1hg4qqfd_?entry=ttu"
%}


Please address any packages to:

*Michael Robben*\
*1201 W Gregory Drive*\
*212 ERML*\
*Urbana, IL 61801*


{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Gallery/ERML.jpg"
  caption="Edward R. Madigan Laboratory"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Gallery/Lab_finished.jpg"
  caption="I-LAMB Laboratory"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

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
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %} -->

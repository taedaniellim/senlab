---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Postdoctoral research positions are available. Potential candidates for postdocs must provide a detailed CV as well as the complete contact information of three professional references. Current graduate students who are interested in doing a rotation in the Şen Lab must provide a detailed résumé or CV. References are optional for graduate students.

Undergraduates wishing to complete an honors thesis as a volunteer in the Lab should view the flyer before submitting an application.

{%
  include button.html
  type="email"
  text="SenLab@uh.edu"
  link="SenLab@uh.edu"
%}
{%
  include button.html
  type="phone"
  text="713-743-1083"
  link="+1 713-743-1083"
%}
{%
  include button.html
  type="SERC Building 545, W4010E University of Houston"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% capture col2 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% capture col3 %}
<!-- Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor -->
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
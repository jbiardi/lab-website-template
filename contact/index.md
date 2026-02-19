---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

You can reach Dr. James Biardi using the contact information below. His office is located on the Fairfield University campus in the Department of Biology.

{%
  include button.html
  type="email"
  text="jbiardi@fairfield.edu"
  link="mailto:jbiardi@fairfield.edu"
%}
{%
  include button.html
  type="phone"
  text="(203) 254-4000"
  link="tel:+12032544000"
%}
{%
  include button.html
  type="address"
  tooltip="View on Google Maps"
  link="https://www.google.com/maps/search/1073+North+Benson+Road,+Fairfield,+CT+06824"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/biardi.jpg"
  caption="Dr. James Biardi"
%}

{% endcapture %}

{% capture col2 %}

Fairfield University  
Department of Biology  
1073 North Benson Road  
Fairfield, CT 06824  

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

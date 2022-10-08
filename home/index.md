---
title: Home
nav:
  order: 0
  tooltip: Homepage of lavi
---

<!-- <font face="Arial" size=5><p align="left">LaVi Lab strives to build interactive AI systems
that can not only understand and recreate the visual world but also communicate
like human using natural language.</p></font> -->


<!-- <font face="Arial" size=6>Highlights</font> -->
{% capture text %}
<font face="Arial" size=4><p align="left">We do research on next-generation AI systems
that enable more intelligent interactions. Our research topics are under the umbrella
of Artificial Intelligence, with a focus on Vision + Language, NLP, and general machine
learning approaches.</p></font>


{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/re4.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

{:.center}
{% endcapture %}


{% capture text %}
<font face="Arial" size=4><p align="left">We are a team of enthusiastic researchers that want to push the frontier of AI research. We are committed to doing meaningful and interesting research.</p></font>


{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team2.png"
  link="team"
  title="Our Team"
  text=text
  flip=true
%}



---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [Department of Computer Science and Engineering](https://www.cse.cuhk.edu.hk/), [the Chinese University of Hong Kong](https://www.cuhk.edu.hk/).

{%
  include link.html
  type="email"
  icon=""
  text="lwwang@cse.cuhk.edu.hk"
  tooltip=""
  link="lwwang@cse.cuhk.edu.hk"
  style="button"
%}
<!-- {%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Department+of+Computer+Science+and+Engineering/@22.4179337,114.2072318,21z/data=!4m5!3m4!1s0x3404089c4ee561eb:0x4901d620835ff29e!8m2!3d22.4179185!4d114.2072256"
  style="button"
%} -->
{:.center}

{% include section.html %}

<!-- ### <i class="fas fa-mail-bulk"></i>Mailing Address -->

{% capture col1 %}
{%
  include figure.html
  image="images/cuhk.png"
  caption="The Chinese University of Hong Kong"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/cuhk_cse.jpg"
  caption="Department of Computer Science and Engineering"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}

---
title: Team
nav:
  order: 3
  tooltip: About our team
---
# <i class="fas fa-users"></i>Team
**<center><font face="Arial" size=5>Principal Investigator</font></center>**

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}


**<center><font face="Arial" size=5>Vision + Language Group @ LaVi</font></center>**
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group: vl"
%}{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ra, group: vl"
%}{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mphil, group: vl"
%}

**<center><font face="Arial" size=5>NLP Group @ LaVi</font></center>**

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group: nlp"
%}{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mphil, group: nlp"
%}
{:.center}
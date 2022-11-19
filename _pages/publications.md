---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


## Publications

<b>All Eyes On Me: Inside Trackers’ Exfiltration of PHI from Healthcare Providers’ Online Systems.</b><br>
<b>Mingjia Huo</b><br>, Maxwell Bland, Kirill Levchenko
Uma Girish, Avishay Tal, <b>Kewen Wu</b><br>
<i>Proceedings of the 21st Workshop on Privacy in the Electronic Society (WPES), 2022</i>.<br>
[WPES](https://dl.acm.org/doi/10.1145/3559613.3563190) 

---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am an assistant professor of data science and business analytics at KEDGE Business School.

Research Interest
------
My research focuses on data-driven decision making under uncertainty. I seek to provide both methodologies and practical solutions that combine tools and concepts from machine learning, operations research, and geoinformatics. From an application perspective, my research focuses on supply chain management and crisis management.

- Predictive & prescriptive analytics
- Data-driven decision-making
- Decision support system
- Geoinformatics

Selected Publications
------
{% assign all_pubs = site.data.publications | sort: "year" | reverse %}
<ol>
{% for pub in all_pubs %}{% if pub.selected %}{% include pub-item.html pub=pub %}{% endif %}{% endfor %}
</ol>

[Full list of publications](/research/)

Education
------
- Ph.D. in Cartology & Geographic Information System<br />
  Peking University (2015 - 2020)
- B.E. in Information Engineering (Instrument & Optoelectronic)<br />
  Beihang University (2011 - 2015)
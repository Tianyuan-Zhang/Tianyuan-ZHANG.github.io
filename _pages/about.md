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
My research focuses on data-driven decision making under uncertainty. I seek to provide both methodologies and practical solutions that combine tools and concepts from machine learning, operations research, and geoinformatics. From an application perspective, my research focuses on supply chain management and logistics.

- Decision-focused learning
- Predictive & prescriptive analytics
- Supply chain management
- Geoinformatics
- Simulation

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

News
------
- Linda BEN ISMAIL starts her Ph.D. subject "Using data analytics for the design of robust supply chains" supervised by [Walid KLIBI](https://scholar.google.com/citations?hl=en&user=KHGNTUAAAAAJ) and me.
- The manuscript of my paper “Coupling simulation and machine learning for predictive analytics in supply chain management” (Joint work with Matthieu LAURAS, Gregory ZACHAREWICZ, Souad RABAH, Frederick BENABEN) is available [here](https://imt-mines-albi.hal.science/hal-04562707/file/Coupling-simulation-machine-learning-predictive-analytics-supply-chain-management.pdf).
- I start as an Assistant Professor of data science and business analytics at KEDGE Business School.

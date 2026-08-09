---
permalink: /
title: "About Me"
seo_title: "Chengyao Yu | Statistics and Reliable AI"
description: "Chengyao Yu is an M.S. student at SUSTech researching reliable artificial intelligence, multiple hypothesis testing, and distribution approximation."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="home-intro">I am an M.S. student in the Department of Statistics and Data Science at the <strong>Southern University of Science and Technology (SUSTech)</strong>.</p>

I am fortunate to be advised by Professor **[Bingyi Jing](https://sai.cuhk.edu.cn/en/teacher/162)**. My research lies at the intersection of statistical theory and reliable artificial intelligence.

<div class="profile-actions" aria-label="Profile links">
  <a class="btn btn--primary" href="/publications/">Publications</a>
  <a class="btn" href="https://scholar.google.com/citations?user=nl83_tUAAAAJ&hl=en" rel="noopener noreferrer">Google Scholar</a>
  <a class="btn" href="https://orcid.org/0009-0008-7259-9100" rel="noopener noreferrer">ORCID</a>
  <a class="btn" href="mailto:12532239@mail.sustech.edu.cn">Email</a>
</div>

# Research Interests

* **Reliable Artificial Intelligence**
* **Multiple Hypothesis Testing**
* **Distribution Approximation**

# Selected Publications

<div class="selected-publications">
{% assign selected_publications = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_publications %}
  {% include archive-single.html %}
{% endfor %}
</div>


# News

* **May 2026:** [Anytime Safe PAC Efficient Reasoning](/publication/2026-01-31-anytime-safe-pac) was accepted at **ICML 2026** and discussed at **ES-Reasoning @ ICLR 2026**.
  
* **October 2025:** [Random Weighting Approximation of M-estimators with Increasing Dimensions of Parameter](/publication/2025-10-15-random-weighting) was accepted by **Statistica Sinica**.


# Education

* **M.S. in Mathematics** (2025 – Present)
  <br>Southern University of Science and Technology

* **B.S. in Applied Statistics** (2021 – 2025)
  <br>Zhejiang Gongshang University (Rank: 1/256)

# PhD Opportunities

I am seeking PhD opportunities in statistics and reliable AI. Please feel free to [contact me](mailto:12532239@mail.sustech.edu.cn) if you are recruiting students in related areas.

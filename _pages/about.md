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

<p class="home-intro">I am an M.S. student in the Department of Statistics and Data Science at the <strong>Southern University of Science and Technology (SUSTech)</strong>.</p> I am very fortunate to be advised by Professor **[Bingyi Jing](https://sai.cuhk.edu.cn/en/teacher/162)**. During my undergraduate studies, I had the privilege of receiving guidance from Professors **[Zhanfeng Wang](https://bs.ustc.edu.cn/chinese/profile-106.html)** and **[Ruixing Ming](https://mypage.zjgsu.edu.cn/tjysjkx/mrx/main.htm)**, and also benefited from the assistance of Professor **[Dongsheng Tu](https://phs.queensu.ca/faculty-research/dongsheng-tu)** and others.

My current research lies at the intersection of statistical theory and artificial intelligence. Recently, I have also been exploring other areas related to embodied intelligence, fields that I find truly fascinating. 

<div class="profile-actions" aria-label="Profile links">
  <a class="btn btn--primary" href="/publications/">Publications</a>
  <a class="btn" href="https://scholar.google.com/citations?user=nl83_tUAAAAJ&hl=en" rel="noopener noreferrer">Google Scholar</a>
  <a class="btn" href="https://orcid.org/0009-0008-7259-9100" rel="noopener noreferrer">ORCID</a>
  <a class="btn" href="mailto:12532239@mail.sustech.edu.cn">Email</a>
</div>

<h1 class="section-heading section-heading--research"><span class="section-heading__icon"><i class="fa-solid fa-atom"></i></span>Research Interests</h1>

* **Embodied Intelligence**
* **Trustworthy AI**
* **Multiple Hypothesis Testing**
* **High-dimensional Asymptotic Theory**

<h1 class="section-heading section-heading--news"><span class="section-heading__icon"><i class="fa-solid fa-bolt"></i></span>News</h1>

* **Sep 2026:** I have been selected for both the *National Scholarship* and the *BYD Scholarship*.

* **Sep 2026:** [Residual Calibration via Local Feature-Space Refinement](/publication/2026-05-22-calibration) was accepted at *NeurIPS 2026*.
  
* **May 2026:** [Anytime Safe PAC Efficient Reasoning](/publication/2026-01-31-anytime-safe-pac) was accepted at *ICML 2026* and discussed at *ES-Reasoning @ ICLR 2026*.
  
* **October 2025:** [Random Weighting Approximation of M-estimators with Increasing Dimensions of Parameter](/publication/2025-10-15-random-weighting) was accepted by *Statistica Sinica*.


<h1 class="section-heading section-heading--publications"><span class="section-heading__icon"><i class="fa-solid fa-book-bookmark"></i></span>Selected Publications</h1>

<p class="publication-legend">(* equal contribution; † corresponding author; ‡ supervised student)</p>

<div class="selected-publications">
{% assign selected_publications = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_publications %}
  {% include archive-single.html %}
{% endfor %}
</div>

<h1 class="section-heading section-heading--services"><span class="section-heading__icon"><i class="fa-solid fa-pen-nib"></i></span>Academic Services</h1>

* **Journal Reviewer:**
  * [IEEE Transactions on Mobile Computing (TMC)](https://ieeexplore.ieee.org/xpl/issues?punumber=7755&isnumber=11676226)

* **Conference Reviewer:**
  * [International Conference on Learning Representations (ICLR)](https://iclr.cc/)
  * [Association for the Advancement of Artificial Intelligence (AAAI)](https://aaai.org/)

<h1 class="section-heading section-heading--education"><span class="section-heading__icon"><i class="fa-solid fa-building-columns"></i></span>Education</h1>

* **M.S. in Mathematics** (2025 – Present)
  <br>Southern University of Science and Technology

* **B.S. in Applied Statistics** (2021 – 2025)
  <br>Zhejiang Gongshang University (Rank: 1/256)

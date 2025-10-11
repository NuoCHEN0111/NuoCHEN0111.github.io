---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .bold-text {
    font-weight: bold;
  }
</style>
<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 160px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>
<style>
.author-footnotes {
  display: flex;
  gap: 20px;
}
</style>
<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About me
Hi, I'm Nuo Chen. I'm currently a Ph.D student at the [Deparmnet of Civil Engineering, the University of Hong Kong (HKU)](https://www.civil.hku.hk) under supervised by [Prof. Clarence E. Choi](https://www.civil.hku.hk/pp-choice.html).Before starting my Ph.D study, I also had a M.Sc degree from HKU and obtained my B.Eng degree from [Central South University (CSU)](https://www.csu.edu.cn) which was advised by [Prof. Jiren Xie](https://faculty.csu.edu.cn/xiejiren/zh_CN/index.htm).

My current research aims to: (1) **track buried objects under debris flow** through different physical scales and provide **reliable disaster reponse** to the urgent needs of society;   (2) develop **scientific machine learning tools** for landslide/debris flow early warning and reconstruction.

# 🔍 Research interests
- Landslides mechanism
- Scientific machine learning in geo-hazard
- Landslides early warning and response

# 🔥 News
- **2025.10**: &nbsp;🎉 New publication! I'm glad my first paper was accepted by **Engineering Geology** based on my Bachelor graduation thesis. As first-author, I kindly thanks all my co-authors, especially Prof. Jiren Xie who was my Bachelor's surpervisor.
- **2025.09**: &nbsp;🎉 I start my PhD study at HKU!

# 📝 Selected Publications 

<div class="author-footnotes"> <span class="bold-text">* Corresponding author </span> <span class="bold-text">† Equal contribution authors at this work </span> </div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Engineering Geology</div><img src='images/EG 2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A real-time prediction method of slope failure using Bayesian approach based on slope surface tilting measurements**](https://nuochen0111.github.io/PDF/EG%202025.pdf)<span class="rucred">**JCR Q1**</span>

**Nuo Chen**, Pengpeng He, Jiaxun Chen, Xiaocheng Huang, Kun Fang, Jiren Xie*, Denis N. Gorobtsov, Margarita A. Novgorodova

**Main Contribution**
- An Update approach combine non-informative prior distributions and the Markov-chain Monte Carlo (MCMC) method for prediction slope failure time based on tilting measurements
- Comparison between the new Bayesian and conventional prediction methods
- Relationship between prediction errors and input data quantity using fifteen laboratory and field cases
</div>
</div>

# 🌏 Collaboration
- [**Prof.Pengpeng He**](https://www.dundee.ac.uk/people/pengpeng-he), **Lecturer**, *University of Dundee (UK, Dundee)*,(**2024.12–Present**) 

# 📖 Educations
- **2025.09–Present**: Ph.D in Geotechnical Engineering  
  – *The University of Hong Kong (China, Hong Kong SAR)*  
- **2024.09–2025.09**: M.Sc in Civil Engineering (Geotechnical Engineering Stream)  
  – *The University of Hong Kong (China, Hong Kong SAR)*  
- **2020.09–2024.06**: B.Eng in Civil Engineering (First class honours) 
  – *Central South University (China, Hunan)*  

<div class="logo-row">
  <img src="../images/CSU.png"     alt="">
  <img src="../images/HKU.png"  alt="">
</div>

<footer class="site-footer">
  <p>&copy; 2025 Nuo Chen. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>

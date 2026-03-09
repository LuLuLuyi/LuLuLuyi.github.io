---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Currently, I am a M.S. Student at [Fudan University](https://www.fudan.edu.cn/en/), advised by Prof. [Tao Gui](https://scholar.google.com/citations?user=h1-3lvwAAAAJ&hl=zh-CN) & Prof. [Xuanjing Huang](https://scholar.google.com/citations?user=y7wVlWkAAAAJ&hl=zh-CN). Previously, I received my B.S. degree from [Northeastern University](http://english.neu.edu.cn/) in 2023, where I was an Outstanding Graduate and ranked 3/221 (top 1%) with a GPA of 4.365/5.0.

My research interests lie in **Complex reasoning** and **long-horizon planning**. I am also interested in downstream applications of LLMs, such as **deep research** and **vibe coding**.

<div align="right">
</div>

{% include_relative includes/pub.md %}

{% include_relative includes/interns.md %}

<!-- {% include_relative includes/talks.md %} -->

{% include_relative includes/honors.md %}

<!-- {% include_relative includes/ta.md %} -->

{% include_relative includes/edu.md %}

<!-- {% include_relative includes/services.md %} -->

<!-- {% include_relative includes/reading.md %} -->

> "What's past is prologue." -- William Shakespeare (The Tempest)

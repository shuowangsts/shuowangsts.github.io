---
# 设置 permalink 为 /zh/
permalink: /zh/
title: "王硕" # 中文标题
excerpt: "STS领域博士候选人" # 中文摘要
author_profile: true
# lang: zh # 可选
---

{% comment %} 移除了之前添加在页面内的语言切换链接 {% endcomment %}

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我叫王硕，非常高兴认识你！

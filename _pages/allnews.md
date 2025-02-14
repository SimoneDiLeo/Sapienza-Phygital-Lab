---
title: "News"
layout: textlay
excerpt: "Sapienza Phygital Lab"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<br>  {{ article.date }} <br> {{ article.headline | markdownify}}
{% endfor %}

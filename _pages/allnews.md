---
title: "SELab->News"
layout: textlay
excerpt: "SELab -- News"
sitemap: false
permalink: /allnews.html
---


<h2 style="font-family: 'Roboto', sans-serif; font-weight: 500; font-size: 32px;">News and Activities</h2>
<br>

{% for article in site.data.news %}
<span style="color: #7a0000;">[{{ article.date }}]</span>
<p><em>{{ article.headline }}</em></p>
{% endfor %}

---
title: "吉林大学建设工程学院张文团队 - 新闻"
layout: textlay
excerpt: "建设工程学院张文团队 at 吉林大学."
sitemap: false
permalink: /allnews.html
---

# 团队新闻

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

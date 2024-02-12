---
title: "Home"
layout: textlay
sitemap: false
permalink: /articles.html
---

# Interesting Reads
{% for article in site.data.news %}
<em>{{ article.headline }}</em>
{% endfor %}

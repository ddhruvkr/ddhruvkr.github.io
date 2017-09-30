---
title: "Home"
layout: textlay
excerpt: "Dhruv Kumar"
sitemap: false
permalink: /articles.html
---

# Things of interest
{% for article in site.data.news %}
<em>{{ article.headline }}</em>
{% endfor %}

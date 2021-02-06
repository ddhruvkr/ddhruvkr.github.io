---
title: "Home"
layout: textlay
excerpt: "Dhruv Kumar"
sitemap: false
permalink: /publications.html
---

{% assign publications = site.data.publications %}
{% for pub in publications %}
<h1>{{ pub.display_year }}</h1>
<em>{{ pub.headline }}</em>
<em>{{ pub.page }}</em>
{% endfor %}



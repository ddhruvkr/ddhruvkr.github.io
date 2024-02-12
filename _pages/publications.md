---
title: "Home"
layout: textlay
sitemap: false
permalink: /publications.html
---

{% assign publications = site.data.publications %}
{% for pub in publications %}
<h1>{{ pub.display_year }}</h1>
<em>{{ pub.headline }}</em>
{% endfor %}

<p>* represents equal contribution</p>
<p>Publications can also be found on [Google Scholar](https://scholar.google.ca/citations?user=IiMW328AAAAJ&hl=en&oi=ao)</p>

---
title: "News"
layout: textlay
excerpt: "SENSE Lab at Polytechnique Montréal."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}

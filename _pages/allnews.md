---
title: "News"
layout: textlay
excerpt: "Zhang Lab at Great Bay University."
sitemap: false
permalink: /news.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}

---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}

</div>

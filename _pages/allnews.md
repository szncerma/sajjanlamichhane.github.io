---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<style>
body {
    text-align: left;
}
</style>
<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}

</div>

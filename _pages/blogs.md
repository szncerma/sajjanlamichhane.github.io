---
title: "Blog"
layout: page
sitemap: false
permalink: /blogs/
---
<style>
code {padding: 6px 8px; font-size: 90%;}
body {
    text-align: justify;
}
.jumbotron {
    text-align: left; 
}
</style>
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }}: <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    </li>
  {% endfor %}
</ul>

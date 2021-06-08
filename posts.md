---
layout: default
title: All posts
permalink: /posts.html
---

# All posts

{% for post in site.posts -%}
* {{ post.date | date: "%-d %B, %Y" }}: [{{ post.title }} {{ post.subtitle }}]({{ post.url }})
{% endfor %}

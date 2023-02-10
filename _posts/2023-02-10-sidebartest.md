---
title: "blog"
layout: archive
permalink: /blog
---

###우와 글이다 그칭 그칭
{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
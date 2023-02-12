---
permalink: /categories/
title: "인공지능공학과"
layout: archive
toc: true
toc_sticky: true
toc_label: "MYSELF"
sidebar: true
---


{% assign posts = site.categories.ise_starterbook %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
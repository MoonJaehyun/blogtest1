---
permalink: /categories/assignment/
title: "assignment"
layout: archive
toc: true
toc_sticky: true
toc_label: "MYSELF"
sidebar: true
---


{% assign posts = site.categories.assignment %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
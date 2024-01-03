---
title: "주목할 뉴스"
layout: archive
permalink: categories/news
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.News %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
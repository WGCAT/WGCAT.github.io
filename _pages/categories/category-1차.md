---
title: "1차"
layout: archive
permalink: categories/1
author_profile: true
sidebar_main: true
---



{% assign posts = site.categories.1 %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}

---
title: "Embedded System"
layout: archive
permalink: categories/embedded
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.Embedded %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
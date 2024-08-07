---
layout: home
title: Welcome to Tripperist
order: 1
---

{% assign about = site.pages | where: 'name','welcome.md' %}
{{welcome}}

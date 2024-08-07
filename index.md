---
layout: home
title: Welcome to Tripperist
order: 1
---

{% assign welcome = site.pages | where: 'name','welcome.md' %}
{{welcome}}

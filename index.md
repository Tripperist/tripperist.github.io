---
layout: home
title: Welcome to Tripperist
---

{% assign welcome = site.pages | where: 'name','welcome.md' %}
{{welcome}}

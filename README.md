---
layout: home
title: Foundations of Privacy
nav_exclude: true
permalink: index.html
seo:
  type: Course
  name: Foundations of Privacy
---

## 18734 / 17731: Foundations of Privacy

Welcome to the course webpage! Some useful links:

- [About](about.md) this course
- [Course calendar](calendar.md)
- Meet our [course staff](staff.md)


## Announcements


{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

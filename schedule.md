---
layout: page
title: Schedule
nav_order: 3
last_modified_date: "now"
description: The weekly event schedule.
---

# Weekly Schedule 🗓️  

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

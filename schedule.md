---
layout: page
title: Schedule
nav_order: 3
last_modified_date: "now"
description: The weekly event schedule.
---

# Weekly Timetable 🗓️  

{% assign schedules = site.schedules %}
{% for schedule in schedules %}
{{ schedule }}
{% endfor %}


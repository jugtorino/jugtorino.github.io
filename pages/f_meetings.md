---
layout: page
title: Meetings
description: Elenco di tutti i meetings
permalink: /meetings/
---

Ecco l'elenco di tutti i meetings tenuti dal JUG Torino:

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})
{% endfor %}

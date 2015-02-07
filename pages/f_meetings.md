---
layout: page
title: Meetings
permalink: /meetings/
---

Ecco l'elenco di tutti i meetings tenuti dal JUG Torino:

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})
{% endfor %}

---
layout: default
title: Home
---

# Latvian Developers Network

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url}}) (*{{ post.date | date_to_string }}*)
{% endfor %}

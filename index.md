---
title: learntechnology.net
layout: default
---

<div class="posts" markdown="1">
{% for post in site.posts %}
- [{{ post.date | date:"%m.%d.%Y" }} &raquo; {{ post.title }}]({{ post.url }}) -- {{ post.content | strip_html | truncate:140 }}
{% endfor %}
</div>	
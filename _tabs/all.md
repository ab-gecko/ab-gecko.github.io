---
layout: page
title: All Poems
icon: fas fa-leaf
order: 1
---
{% for post in site.posts %}
### {{ post.title }}
*{{ post.date | date: "%B %d, %Y" }}*
{{ post.content }}
---
{% endfor %}
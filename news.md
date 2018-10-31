---
title: News
layout: default
---

## News

<div>
{% for post in site.posts %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <h4>{{ post.date | date: "%b %-d, %Y" }}</h4>
    <p>{{ post.excerpt }} <a href="{{ post.url }}">more...</a></p>
{% endfor %}
</div>

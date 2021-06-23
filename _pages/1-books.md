---
layout: page
permalink: /books/
title: Books
---


{% for post in site.categories.books %}
<li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
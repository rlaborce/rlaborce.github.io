---
layout: default
title: Neil Laborce | Memo Archive
description: Archived memos on marketing, growth, leadership, and lessons learned along the way.
index: index, follow
---
<!-- This loops through all posts -->
{% for post in site.posts %}
  <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
  <div class="content">
    <i>{{ post.date | date: "%-d %B %Y" }}</i>
    <br/>{{ post.excerpt }}
  </div>
  <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">[ Read More ]</a>
  <br/>
  <br/>
{% endfor %}

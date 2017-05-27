---
layout: default
title: Blog | Neil Laborce
description: This blog serves as documentation for Neil's progress in webmastering as well as to share some thoughts, insights and daily happenings.
---
<section class="archive-post-list" style="align:center">
   {% for post in site.posts %}
       {% assign currentDate = post.date | date: "%Y" %}
       {% if currentDate != myDate %}
           {% unless forloop.first %}</ul>{% endunless %}
           <h3 style="text-align:center">{{ currentDate }}</h3>
           <ul>
           {% assign myDate = currentDate %}
       {% endif %}
       <li>
       <span class="title"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.post_title }}</a></span>
       <span class="date">{{ post.date | date: "%B %-d" }}</span>
       </li>
       {% if forloop.last %}</ul>{% endif %}
   {% endfor %}

</section>

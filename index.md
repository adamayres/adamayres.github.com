---
layout: page
title: Pass the butta, plz!
hidePageTitle: true
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span class="day">{{ post.date | date: "%d" ) }}</span>
    <span class="month">{{ post.date | date: "%b" ) }}</span>
    <span class="year">{{ post.date | date: "%Y" ) }}</span>
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
  </li>
  {% endfor %}
</ul>



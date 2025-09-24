---
layout: home
title: Welcome
---

# Welcome to My Site

Here are my latest posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a post.url }}{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

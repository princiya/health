---
layout: default
title: My Health Streak
---

## Recent Runs
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date_to_string }})</small>
    </li>
  {% endfor %}
</ul>

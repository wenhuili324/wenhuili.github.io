---
layout: research
title: Research Projects
permalink: /research/
---

<ul class="post-list">
  {% assign projects = site.research | sort: "date" | reverse %}
  {% for project in projects %}
    <li>
      <span class="post-date">{{ project.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
      <p>{{ project.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

{{ post.excerpt }}
<a href="{{ post.url }}">Read more</a>

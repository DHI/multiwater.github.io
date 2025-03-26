---
layout: default
title: "News"
rank: 6
---

# News
Here we post the most recent news and activities, ordered in chronological order from newest to oldest.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

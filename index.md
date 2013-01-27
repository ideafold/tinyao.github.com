---
layout: page
title: Kyle Style
tagline: Deep thoughts
---
{% include JB/setup %}

<ul class="posts list-unstyled">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> <span aria-hidden="true" class="icon-code"></span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



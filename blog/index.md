---
layout: page
title: Welcome!
tagline: but there is not much to see yet..
---
{% include JB/setup %}


Following are the posts in this blog.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

The usefulness of this blog will grow as $$ \Omega(2^n) $$.

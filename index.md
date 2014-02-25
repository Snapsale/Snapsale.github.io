---
layout: page
title: Snapsale
tagline: sell and buy lovely
---
{% include JB/setup %}

{% for post in site.posts %}
  <h2 class="post-title"><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p class="post-meta">{{ post.date | date_to_string }}</p>
  <p class="post-excerpt">{{ post.content }}</p>
{% endfor %}




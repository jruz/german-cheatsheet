---
layout: page
title: Deutsch Spickzettel 
---

{% for post in site.posts %}
  <div class="post">
    <h2>{{ post.title}}</h2>
    {{ post.content }}
  </div>
{% endfor %}

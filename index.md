---
layout: page
title: Blogroll
tagline: Welcome to Amble !
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <div><a href="{{ BASE_PATH }}{{ post.url }}"><h2>{{ post.title }}</h2></a>  <div> {{ post.content }}</div></div>
  {% endfor %}
</ul>



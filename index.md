---
layout: page
title: Snow Hong's Blog
tagline: Supporting tagline
---
{% include JB/setup %}

<!--首页显示post list的地方-->
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




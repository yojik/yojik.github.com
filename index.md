---
layout: page
title:  Yojik の Blog 
tagline: 最初のページ
---
{% include JB/setup %}

## 記事

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; {{ post.category}}: <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do




---
layout: page
title:  記事一覧
---
{% include JB/setup %}
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; {{ post.category}}: <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do
<ul>
	<li>markdown覚える</li>
	<li>レイアウトなおす</li>
	<li>Amazonアフィの手段を検討</li>
</ul>


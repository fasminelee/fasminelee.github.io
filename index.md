---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: fasminelee's Corner
---

<h2>{{ page.title }}</h2>
<p>最新文章</p>
<ul>
	{% for post in site.posts %}
	<li>
    {{ post.date | date_to_string }} 
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  </li>{% endfor %}
</ul>
hhhhhhhhhhhhhhhhhhhhhhhhhhhh
<p><br/><b>My Blog:</b></p>
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &raquo; 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>{% endfor %}
</ul>

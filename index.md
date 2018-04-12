---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: fasminelee's Corner
---

<h2>{{ page.title }}</h2>
<p><br/><b>My Blog:</b></p>
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date_to_long_string }}</span> &raquo; 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>{% endfor %}
</ul>

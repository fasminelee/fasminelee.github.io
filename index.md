---
layout: default
title: Fasmine Lee's Corner
---

<h2>{{ page.title }}</h2>
Hi there, I am Fasmine Lee, an [Open Source][oss] enthusiast.

<p><br/><b>My Blog:</b></p>
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &raquo; 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>{% endfor %}
</ul>

<p><b>Find me on:</b></p>
<ul>
  <li><a href="http://github.com/fasminelee/">Github</a></li>
</ul>
<p><br /><b>Contact Information:</b></p>

<blockquote>联系 fasminelee@gmail.com</blockquote>


[oss]:http://en.wikipedia.org/wiki/Open_source
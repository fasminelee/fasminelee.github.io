---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: fasminelee's Corner
---

Hi there, I am Fasmine Lee, an [Open Source][oss] enthusiast. This site is
dedicated to providing information about [me](resume.html) and [what I do](/work).
<!-- I am a screencastr at <http://haoduoshipin.com>. -->
<p><br/><b>My Blog:</b></p>
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &raquo; 
    <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<p><b>Find me on:</b></p>

<ul>
  <li>
    <a href="http://github.com/fasminelee/">Github</a>
  </li>
</ul>
<p><br /><b>Contact Information:</b></p>

<blockquote>
  联系 fasminelee@gmail.com
</blockquote>

[oss]:http://en.wikipedia.org/wiki/Open_source
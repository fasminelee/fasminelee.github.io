---
layout: default
title: Fasmine Lee's Corner
---

<h2>{{ page.title }}</h2>
Hi there, I am Fasmine Lee, an [Open Source Software][oss] enthusiast.

<p><br/><b>My Blog:</b></p>
<!-- <ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo;<a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul> -->
<ul class="posts">
  {% for post in paginator.posts %}
    <article>
      <header>
        <a href="{{ site.baseurl | prepend: site.url  }}/archive/#{{ post.date | date: '%Y-%m-%d' }}"><span class="octicon octicon-calendar"></span>&nbsp;<span>{{ post.date | date: "%Y-%m-%d" }}</span></a>
      </header>
    <div class="module">
      <a class="title" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>
      <p>{% if post.excerpt.size > 32 %}{{ post.excerpt }}{% else %}{{ post.content | strip_html | strip_newlines | truncate: 160 }}{% endif %}</p>
      <a class="readmore" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">Read More</a>
      <footer>
        {% for tag in post.tags %}
          <a class="word-keep" href="{{ site.baseurl | prepend: site.url }}/tags/#{{ tag }}">
            <span class="octicon octicon-tag"></span>&nbsp;{{ tag }}</a>
        {% endfor %}
        <span class="word-keep pull-right">
          <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}#post-comment">
            <span class="octicon octicon-comment"></span>&nbsp;Comment
          </a>
          <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}#post-share">
            <span class="octicon octicon-file-symlink-file"></span>&nbsp;Share
          </a>
        </span>
      </footer>
    </div>
    </article>
  {% endfor %}
</ul>

<!-- pagination -->
<nav class="text-center">
  <ul class="pagination">
    {% if paginator.total_pages > 1 %}
      {% if paginator.previous_page %}
        <li><a href="{{ paginator.previous_page_path | prepend: site.baseurl | prepend: site.url }}" aria-label="Previous"><span aria-hidden="true">&laquo;</span></a></li>
      {% endif %}
      {% for page in (1..paginator.total_pages) %}
        {% if page == paginator.page %}
          <li class="active"><span>{{ page }}</span></li>
        {% elsif page == 1 %}
          <li><a href="{{ '/' | prepend: site.baseurl | prepend: site.url  }}">{{ page }}</a></li>
        {% else %}
          <li><a href="{{ page |  prepend: '/' | prepend: site.baseurl | prepend: site.url }}">{{ page }}</a></li>
        {% endif %}
      {% endfor %}
      {% if !paginator.next_page %}
        <li><a href="{{ paginator.next_page_path | prepend: site.baseurl | prepend: site.url }}" aria-label="Next"><span aria-hidden="true">&raquo;</span></a></li>
      {% endif %}
    {% endif %}
  </ul>
</nav>


[oss]:http://en.wikipedia.org/wiki/Open_source
---
layout: default
title: Fasmine Lee's Corner
---

<h2>{{ page.title }}</h2>
Hi there, I am Fasmine Lee, an [Open Source Software][oss] enthusiast.

<p><br/><b>My Blog:</b></p>
<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &raquo; 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>{% endfor %}
</ul>

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
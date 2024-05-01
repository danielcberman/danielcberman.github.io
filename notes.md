---
layout: base
title: Notes
permalink: /notes/
---

<ul class="post-list">
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
{%- for note in site.notes | sort: "date_format" -%}
<li>
<span class="post-meta">{{ note.date | date: date_format }}</span>
<h3><a class="post-link" href="{{note.url}}">{{note.title | escape}}</a></h3>
<p>{{note.excerpt | strip_html | strip_newlines | truncatewords: 50}}</p>
</li>
{% endfor %}
</ul>
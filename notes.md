---
layout: base
title: Notes
permalink: /notes/
---

<ul class="post-list">
{% for note in site.notes | sort: "date" %}
<li>
<span class="post-meta">{{ note.date | date: date_format }}</span>
<h3><a class="post-link" href="{{note.url}}">{{note.title | escape}}</a></h3>
<p>{{note.excerpt | strip_html | strip_newlines | truncatewords: 50}}</p>
</li>
{% endfor %}
</ul>
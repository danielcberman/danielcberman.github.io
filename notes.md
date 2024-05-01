---
layout: base
title: Notes
permalink: /notes/
---

{% for note in site.notes | sort: "date” | reverse%}
<div>
<p><a href=“{{note.url}}”>{{note.title}}</a></p>
<p>{{note.excerpt | strip_html | strip_newlines | truncatewords: 50}}</p>
</div>
{% endfor %}
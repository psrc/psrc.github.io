---
layout: default
title: Authors of PSRC I/O
---

## Who's writing all this stuff? Here's the rundown.

<table class="author_table">
{% for person in site.authors %}
	<tr><td class="author_table">
		<img src="{{person.image}}" alt="{{person.name}}" width="80">
	</td><td class="author_table">
		<p><strong>{{person.name}}</strong>. {{person.blurb}}</p>
	</td>
	</tr>
{% endfor %}
</table>


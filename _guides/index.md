---
title: Designing a register people will trust
layout: default
permalink: /guides/index.html
item_name: ''
---

Learn about designing collaborative open registers with robust governance and get help
managing them once they're published.


{% assign items = site.guides | sort: 'number' %}
{% for item in items %}
{% if item.url != '/guides/index.html' %}

<div class="card">
<div class="card-header">
<h3>
<a href="{{ site.baseurl }}{{ item.url }}">
{{ item.title }}
</a>
</h3>
</div>
</div>

{% endif %}
{% endfor %}

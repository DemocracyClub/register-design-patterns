---
title: Designing a register people will trust
layout: default
category: "1. Introduction"
---

Learn about designing collaborative open registers with robust governance and get help
managing them once they're published.


<div class="container">
<div class="fukol-grid">


{% assign items = site.guides | sort: 'number' %}
{% for item in items %}
{% if item.url != '/guides/index.html' %}
<div class="card odi-{% cycle "purple", "orange", "pink", "light-blue", "red" %}">
<a href="{{ site.baseurl }}{{ item.url }}">
<h3 class="card-header">
{{ item.title }}
</h3>
</a>
</div>

{% endif %}
{% endfor %}

</div>
</div>

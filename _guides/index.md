---
title: Designing a list people will trust
layout: base
permalink: /guides/index.html
item_name: ''
---

Learn about designing collaborative open lists with robust governance and get
help managing them once they're published.


<div class="container">
<div class="columns">
{% assign items = site.guides | sort: 'number' %}
{% for item in items %}
{% if item.url != '/guides/index.html' %}
<div class="col-4 col-mx-auto col-mr-auto card-collection">
<a href="{{ site.baseurl }}{{ item.url }}">
<div class="card odi-{% cycle "purple", "orange", "pink", "light-blue", "red" %}">
<h3 class="card-header">
{{ item.title }}
</h3>
<div class="card-body">
<p>{{ item.short_desc }}</p>
</div>
</div>
</a>
</div>

{% endif %}
{% endfor %}

</div>
</div>

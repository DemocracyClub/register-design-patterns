---
layout: base
title: Register design patterns
permalink: /governance_patterns/index.html
item_name: ''
category: pattern
---


Governance describes the process of maintaining a list. That is, governance
includes how and when information in a list is added, removed or changed and
who does the updating.

Understanding the governance of a list allows people considering using the
register to make informed decisions about how much they can rely on it.

<div class="container">
<div class="fukol-grid">

{% for item in site.governance_patterns %}
{% if item.url != "/governance_patterns/index.html" %}
<div class="card odi-{% cycle "purple", "orange", "pink", "light-blue", "red" %}">
<a href="{{ site.baseurl }}{{ item.url }}">
<h3 class="card-header">
{{ item.title }}
</h3>
<div class="card-body">
<p>{{ item.short_desc }}</p>
</div>
</a>
</div>
{% endif %}
{% endfor %}

</div>
</div>

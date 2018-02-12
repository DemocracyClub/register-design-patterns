---
layout: default
title: Governance patterns
permalink: /governance_patterns/index.html
item_name: ''
---


Governance describes the process of maintaining a register. That is,
governance includes how and when information in a register is added, removed
or changed and who does the updating. Understanding the governance of a
register allows people considering using the register to make informed
decisions about how much they can rely on it.

<div class="container">
<div class="columns">

{% for item in site.governance_patterns %}
{% if item.url != "/governance_patterns/index.html" %}
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

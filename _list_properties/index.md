---
permalink: /list_properties/index.html
title: Properties of lists
layout: default
item_name: ''
---

These categories should be considered as having soft, porous edges, and have been created by examining a large number of lists during the course of this research, as well as noting the way in which people discuss them and describe their key features.

Due to the scope of this work, we have not attempted to create an academically rigorous and extensively validated framework for list categorisation, although we would welcome such work were it conducted and widely disseminated.


<div class="container">
<div class="columns">

{% for item in site.list_properties %}
{% if item.url != "/list_properties/index.html" %}
<div class="col-4 card-collection">
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

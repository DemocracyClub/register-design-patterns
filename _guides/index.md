---
title: Designing a register people will trust
layout: default
permalink: /guides/index.html
item_name: ''
---

Learn about designing collaborative open registers with robust governance and get help
managing them once they're published.

<div class"container">
<div class="columns">
    <div class="col-6">
    <h2>
        If you're currently asking...
    </h2>
    <ul>
        {% for item in site.guides %}
            {% if item.url != '/guides/index.html' %}
                <li>
                    <a href="{{ site.baseurl }}{{ item.url }}">
                        {{ item.title }}
                    </a>
                </li>
            {% endif %}
        {% endfor %}
    </div>
    <div class="col-6">
    <h2>
        Making a register
    </h2>
    </div>
</div>
</div>

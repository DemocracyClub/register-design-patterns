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


<ul>
    {% for item in site.governance_patterns %}
    {% if item.url != "/governance_patterns/index.html" %}
    <li>
        <h3>
            <a href="{{ site.baseurl }}{{ item.url }}">
                {{ item.title }}
            </a>
        </h3>
        <p>{{ item.short_desc }}</p>
    </li>
    {% endif %}
    {% endfor %}
</ul>

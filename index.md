---
title: "Register design patterns"
layout: default

---
# Intro to design patterns

This site is designed to list types of "list" and patterns for maintaining them.

The term list is used to mean a list of _things_ that is kept for some reason. It's an intentionally vague term, partly because there isn't a single term that can describe everything we want to and partly because "database", "register", "code list" and other terms all have specific meanings to some people.

It follows a report about collaborative registers written for [The ODI][odi] by [Open Health Care][ohc] and [Democracy Club][dc].

## Properties of lists

In the report we tried to enumerate interesting properties of registers. We defined a list of terms that could be applied to any

{% for item in site.list_properties %}
<h3><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></h3>
{% endfor %}






[odi]: https://theodi.org/
[ohc]: http://openhealthcare.org.uk/
[dc]: https://democracyclub.org.uk


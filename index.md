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

## Governance patterns

Understanding governance systems is critical to the trustworthiness of a list, yet they are often not explained well.

For instance, registers that have a strong authority ([Foreign and Commonwealth Office’s register of countries recognised by the UK](https://country.register.gov.uk/)) have an obfuscated governance model. The custodian is named, but how that person makes decisions about the register is unknown.

Particularly for lists which are designed as data infrastructure (called 'registers' in the UK government context) due to the social, environmental or economic value of their contents, explaining the governance process should be considered a minimum requirement.

Similarly those processes must be both transparent and open.

It's possible that organisational boundaries or systems aren't a helpful way to think about governance or collaboration with others.

For example, a list of shops maintained by a company could be wrong because the team who publishes the list doesn't talk to the  team in charge of opening and closing new stores. If each store manager can set their own opening times then it's unlikely any one person within the organisation will be able to confidently publish a list of all the opening times.

We have tried to define a set of patterns that we think are worth considering when creating or maintaining lists.


<ul>
{% for item in site.governance_patterns %}
<li>
    <h3><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></h3>
    <p>{{ item.short_desc }}</p>
</li>
{% endfor %}
</ul>






[odi]: https://theodi.org/
[ohc]: http://openhealthcare.org.uk/
[dc]: https://democracyclub.org.uk


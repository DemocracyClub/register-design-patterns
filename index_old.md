---
title: Designing a list people will trust
layout: page
category: "1. Introduction"
---

Learn about designing collaborative open lists with robust governance and get
help managing them once they're published.


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

<hr>
## The bit about how we did this

Where it goes, nobody knows.


To make these patterns we created a list of lists that we though were
interesting. This list wasn't designed to be complete or objectively the most
interesting lists we could have used.

They were selected by asking people in the ODI network about lists they
maintain as well some lists that the authors already knew about.

You can see and contribute to this list here:

https://docs.google.com/spreadsheets/d/19BPtRKkWAZIFAax24KC2R6-uXPoxIH2a1Lzl1-v
W8sc/edit#gid=0

We then tried to assign attributes to some of the lists. Most of the
attributes act like mutually exclusive tags on a scale, for example
"completeness".

Not all tags are interesting to all lists.

For example in the list of [Microsoft supported
software](https://support.microsoft.com/en-gb/lifecycle/search?ts=-3) the
maintenance of the list is done entirely by Microsoft by some internal
process. This is fairly common for lists.

The interesting thing is that by existing it [changes reality][relation] and
it's logically [complete][completeness].

By comparison the interesting qualities of
[OpenStreetMap](https://www.openstreetmap.org/) are that it's [authority is
verifiable by observation][authority], it's [reality describing][relation] and
it has a [direct access][direct_access] model of maintenance.

The grouped list is here:

https://docs.google.com/spreadsheets/d/1eLmRzkKFJx6hpOcVTv6WmcFYOULCB0SWSOCN0lF
5O1Q/edit#gid=0

After creating this list and validating the patterns we'd found we starting
explaining them. That's the work you can see on this site.




[relation]: {{ site.baseurl }}{% link _list_properties/relation-to-reality.md %}
[primaryness]: {{ site.baseurl }}{% link _list_properties/primaryness.md %}
[completeness]: {{ site.baseurl }}{% link _list_properties/completeness.md %}
[accuracy]: {{ site.baseurl }}{% link _list_properties/accuracy.md %}
[authority]: {{ site.baseurl }}{% link _list_properties/authority.md %}
[direct_access]: {{ site.baseurl }}{% link _governance_patterns/direct_access.md %}

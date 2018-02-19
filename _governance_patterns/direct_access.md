---
title: "Direct access"
layout: post
short_desc: "Edits are made directly with the option of roll back at a later date."
category: pattern
---

## Strengths

The most permissive change model is to provide tools that allow anyone to
directly alter the register. These tools may be an online service acting in a
wiki style, or they may be paper forms that one fills in and then sends to the
custodian responsible for compiling or publishing the register itself.

## Weaknesses

Direct access models must provide some mechanism to deal with vandalism or
fraudulent entries, and frequently include a more proactive mechanism for
reporting inaccuracies. Particularly with official registers which carry some
legal weight there may be penalties for deliberately entering misinformation
into a register.

## Discussion

Where registers using this model have been created in the recent past, they have
tended be created alongside and evolve with tools explicitly designed to
facilitate these governance processes. This frequently includes some sort of
version control system that allows other users (sometimes only with special
permissions) to roll back malicious or accidental changes. The penalty for
vandalism in such cases is often a ban on a particular user.

In such cases, the governance model and the register are so closely linked that
they are almost the same thing.

In practice, many registers operate a mixed governance model. This allows
maintainers to spend their time more effectively by focussing on tasks or areas
which are particularly complex or sensitive while allowing other people to
effectively collaborate on the maintenance of the register.

For example, [Companies House][companieshouse] allows essentially direct access to many
operations, such as creating a new company or recording a share issue. In these
cases a form is submitted, but not checked beyond minimal validation. However
when a company is struck off, it is only possible to record this if one is in
fact the custodian for that piece of information.

Similarly, with crowdsourced lists such as [Wikidata][wikidata], while the default is direct
access to create, alter or remove entries, certain pages are protected. This
changes the default behaviour such that only administrators can make such changes.

## Appropriate for

* [Reality Describing][relation]
* [Secondary Registers][primaryness]

## Examples

* [Wikidata][wikidata]
* [OpenStreetMap][osm]
* [Democracy Club Candidates][candidates]

## Alternative names

* Post-hoc moderation
* Wiki
* Crowdsourcing


[wikidata]: https://www.wikidata.org/wiki/Wikidata:Main_Page
[osm]: https://wiki.openstreetmap.org/wiki/Beginners_Guide_1.3
[candidates]: https://candidates.democracyclub.org.uk/
[relation]: {{ site.baseurl }}{% link _list_properties/relation-to-reality.md %}
[primaryness]: {{ site.baseurl }}{% link _list_properties/primaryness.md %}
[companieshouse]: http://companieshouse.gov.uk/

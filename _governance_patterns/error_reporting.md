---
title: "Error Reporting"
layout: page
short_desc: "Anyone can report and error to a person, organisation or through a process."
category: pattern
---


## Strengths

 If all users of a list are allowed to report errors then there is a higher chance they are discovered. Error reporting allows the governance system to investigate errors without requiring everyone to be able to edit the data directly.

## Weaknesses

Reporting mechanisms might not be obvious or understood. Reports might opinions rather than errors. Management of user feedback has an overhead.

## Discussion

This is the simplest form of collaboration, where anyone can report and error
to a person, organisation or through a process. Error repointing works for all
forms of governance.

Error reporting is different from other patterns like [suggested edits][suggested_edits] because a maintainer needs to triage and apply any fixes themselves.

Error reports can be improved by making the progress of a report easy to follow by the reporter. An [audit trail][audit_trail] linked to the error report might help.

## Appropriate for

* Everything

## Examples

* National Heritage List for England  reporting 'Minor&nbsp;Amendments'

#### Case study

The list of "listed" buildings in the UK maintained by Historic England publishes [guidance on reporting "minor amendments"][minor_amendments]:

> With almost 400,000 entries on the National Heritage List for England (NHLE), many of which are over 20 years old, we realise that there may be a number of minor errors. Here you can find out how to report minor amendments and how we deal with them.

Reporting an error starts a process of investigation, possible updates to the list and feedback to the initial reporter and "any interested parties".


## Further reading

* [Linus's Law](https://en.wikipedia.org/wiki/Linus%27s_Law)

[minor_amendments]: https://historicengland.org.uk/listing/the-list/minor-amendments/

[suggested_edits]: {{ site.baseurl }}{% link _governance_patterns/suggested_edits.md %}
[audit_trail]: {{ site.baseurl }}{% link _governance_patterns/audit-trails.md %}

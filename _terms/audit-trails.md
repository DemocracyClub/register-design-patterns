---
title: "Audit Trail"
layout: page
short_desc: "A log of changes made"
category: pattern
---
An audit trail is a a chronological record of the new entries, removals and updates to entries on a list.
Knowing how a list has changed over time is useful for users trying to see what changes might have been made recently,
but also to convey that the list is 'active' and maintained.
If a user has an outdated version of the list then, depending on the implementation, they can compare changes.

One weakness of audit trails is that mistakes can show up in the historical records, which is a potential
cause of confusion. Depending on the governance type, vandalism can be persisted and presented alongside
the unvandalised list.

## Examples

* [DCLG Local authority register GitHub commits](https://github.com/openregister/local-authority-data/commits/master)
* [Democracy Club version history for Zac Goldsmith](https://candidates.democracyclub.org.uk/person/502#version-667ddc8206bf2967)

## Alternative names

* Commit log
* History

---
title: Custodial discretion
layout: page
short_desc: "For some lists there is an obvious decision maker who operates
upon the contents of the list by fiat."
category: pattern
---

## Strengths

A custodial allows for clear lines of responsibility over changes to a
list. If a person has an official responsibility for maintaining a list
then there is less chance of a data version of the ["bystander
effect"](https://en.wikipedia.org/wiki/Bystander_effect) happening.

## Weaknesses

While errors can be fixed by the right person within the
organisation that created the list, finding that person is often hard and
formal [error reporting][error_reporting] mechanisms may not exist.


This model is poorly suited to [reality describing][relation-to-reality] lists
because there is no logical custodian for things that describe the world.

It only works for [reality altering][relation-to-reality] lists when the
custodian is always involved in the change process.

A lot of lists don't have a logical custodian even though they could in theory.

Only works for small lists where someone can reasonably manage it all. Larger lists might not be able to be managed as well as they would be using other governance patterns.

## Discussion

For some lists there is an obvious decision maker who operates upon the
contents of the list by fiat. This is most commonly due to having either
legislative custodianship or institutional authority.

For instance, when Google decide to no longer support the Mosaic web browser
and remove it from their list of supported web browsers, this decision is
taken by a person or group who have been given executive power over it. This
will result in Mosaic being removed from the list of supported web browsers.

If one happens not to be the custodian the ability to affect change in the
list is [dramatically reduced][change-the-world].

In some cases there may be a clear mechanism to [provide
feedback][error_reporting] which provides some opportunity to [request
additions or corrections][suggested_edits], but this is not always the case.

It's possible for Registers which operate a custodial discretion model operate
on a whim, or make decisions in a smoke filled room with minimal transparency
over the precise process.

Despite this a custodian with proper authority provides much more ability to
[make a promise][what-is-a-register] about the list.

A list made without a logical custodian needs other patterns of governance to
be done well.

For reality describing lists a custodian is the best way to maintain them.

## Appropriate for

* [Primary lists][primaryness]
* [Reality altering][relation-to-reality]


### Examples

* A level English literature set texts
* Directors of a company
* Microsoft supported browsers
* FCO list of countries recognised by the UK


[primaryness]: {{ site.baseurl }}{% link _list_properties/primaryness.md %}
[relation-to-reality]: {{ site.baseurl }}{% link _list_properties/relation-to-reality.md %}
[error_reporting]: {{ site.baseurl }}{% link _governance_patterns/error_reporting.md %}
[suggested_edits]: {{ site.baseurl }}{% link _governance_patterns/suggested_edits.md %}
[change-the-world]: {{ site.baseurl }}{% link _governance_patterns/change-the-world.md %}
[what-is-a-register]: {{ site.baseurl }}{% link _guides/what-is-a-register.md %}

---
title: Design consideration for publishing lists
number: 1
layout: page
---

## Be a good data citizen

Start with <a href="https://theodi.org/guides">best practices for data publishing</a> and apply them to your list.

## User needs for data

Best in class design thinking [starts with needs](https://web.archive.org/web/20140628221103/https://www.gov.uk/design-principles). The hard thing is working out whose needs you need to start with.

For products and services the needs of the end user and any admin users or maintainers are the obvious starting points, however for lists the users should not be confused with the users of the end product that the data is used for.

For example, the [FCO register of countries](https://country.register.gov.uk/) is used on the [register to vote service](https://www.gov.uk/register-to-vote), but the users of the register are not the people registering to vote.

Thinking about the needs of lists is like thinking about the needs of electricity or a can of blue paint. The users want things like reliability and consistency, and they want those things in turn because they want a cup of tea, or blue walls.


A ‘field’ is sometimes called a ‘value’ and is a piece of information that in a spreadsheet would be held in a cell, or on a web site might appear in an input area on a form.

Fields have names, and store information of a particular type. For example a “date of birth” field would contain a date, or a “name” would include the text of someone’s name.

It's important to think hard about the fields in a list. Start by asking the following questions:

### What are the user needs for each field?

Think about user needs for each field as well as the list itself.

### Is there a standard that can be used to represent the data?

Start with simple standards like [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) for dates or [ISO 3166-1](https://en.wikipedia.org/wiki/ISO_3166-1) for countries. Using standards here will made your list easier for people to use.

### Should this field actually link to another list?

If the data in the field is contained in another list then consider linking to that list rather than duplicating it. This is especially true if you don't know the origin of the data.

Linking doesn't have to be any more advanced than using the identifier defined in the other list and documenting the list used. If more than one list is linked to then a `[CURIE](https://en.wikipedia.org/wiki/CURIE)` can be used.

There are many options for linking data and those options are outside of the scope of these guides.

### What is the origin of the data in each field?

Depending on the governance pattern you might not know when all the fields change.

For example, a supermarket company might publish a list of shop locations.

This list would contain thinks like the name, address, phone number, opening times and maybe coordinates of the shop.

Imagine if the opening times could be decided by each shop manager themselves. It might be possible to survey them all periodically to confirm the opening times are correct, but as the creator of the list you can't [promise that the data will always be correct][what-is-a-register].

Just because you can't promise a fields accuracy doesn't mean you shouldn't include it, but if you do you need to consider ways of explaining the chance of error to 3rd parties.

It might be better to split the register in to two at this stage: one that only contains fields you can make a promise about and one with additional fields that contains warnings.

## How to decide on identifiers

Sometimes a list of things might contain an identifier for other identifiable things. For example, a list of schools might contain a local authority that manages that school.

It's tempting to use this ID when creating your ID system. This would allow users of the ID to understand more about the thing, just by looking at the ID.

For example, a school might exist in a local authority with an ID of 42. This means you could make an ID that looks something like `42-01` for the first school in that authority, `42-02` for the next, and so on.

This system has the advantage that the authority is known by looking at the ID, but you are still in control of issuing new IDs.

In this example, you must still ask questions about the ID issuing authority. How will your IDs change if two local authorities merge in to one? If the authority changes its name or boundaries, does it get a new ID?

If you are making IDs about a list of thing that you control, it is best to avoid relying on other IDs, unless you are sure the other ID system will work with your list when it's changed.


[what-is-a-register]: {{ site.baseurl }}{% link what-is-a-register.md %}

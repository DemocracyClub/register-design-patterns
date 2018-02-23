---
title: How to decide on fields
number: 6
layout: page
---

A ‘field’ is sometimes called a ‘value’ and is a piece of information that in a spreadsheet would be held in a cell, or on a web site might appear in an input area on a form.

Fields have names, and store information of a particular type. For example a “date of birth” field would contain a date, or a “name” would include the text of someone’s name.

It's important to think hard about the fields in a list. Start by asking the following questions:

### What are the user needs for each field?

Think about [user needs][user_needs] for each field as well as the list itself.

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


[user_needs]: {{ site.baseurl }}{% link _terms/user-needs-for-data.md %}
[what-is-a-register]: {{ site.baseurl }}{% link what-is-a-register.md %}

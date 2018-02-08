---
title: Decide on fields
number: 6
layout: default
---

A ‘field’ is sometimes called a ‘value’ and is a piece of information that in a spreadsheet would be held in a cell, or on a web site might appear in an input area on a form.

Fields have names, and store information of a particular type. For example a “date of birth” field would contain a date, or a “name” would include the text of someone’s name.

It's important to think hard about the fields in a register. Start by asking the following questions:

### What is the origin of the data in each field?

Depending on the [governance pattern][governance_pattern] you might not know when all the fields change.

For example, a supermarket company might publish a register of shop locations.

This register would contain thinks like the name, address, phone number, opening times and maybe coordinates of the shop.

Imagine if the opening times could be decided by each shop manager themselves. It might be possible to survey them all periodically to confirm the opening times are correct, but as the creator of the register you can't _promise_ that the data will always be correct.

Just because you can't promise a fields accuracy doesn't mean you shouldn't include it, but if you do you need to consider ways of explaining the chance of error to 3rd parties.

It might be better to split the register in to two at this stage: one that only contains fields you can make a promise about and one with additional fields that contains warnings.


[governance_pattern]: {% link _governance_patterns/index.md %}

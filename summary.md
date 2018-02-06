## Almost all list are collaborative

Depending on how you define collaboration. We define reporting errors as a form of collaboration, and almost all lists will allow this.

The collaborative aspects might not be the interesting part of a list. Wikidata makes collaboration core to its product, but not all lists on Wikidata are interesting _because_ of collaboration.

For example, the Historic England list of Listed Buildings is in Wikidata with editing facility, however because this list is a **Secondary Derived** editing it isn't useful.



## Collaboration makes list better

That is, most forms of collaboration are some form of improvement to the list, even if it's in the form of error reporting.

The more effort put in to collaboration the better the list will be [[citation needed]].


## Thoughts Wikidata

Wikidata allows people to make data more useful in the way Greasemonkey allows 3rd parties to edit how browsers render websites.

Let's compare Greasemonkey to GitHub forks and think about the feedback mechanism to authors of the original source.

Wikidata's value is in making any list addressable and linked to other lists. This doesn't address accuracy or collaboration.

A lot of data cleaning work is done before adding to Wikidata and editing errors on Wikidata might not be a useful thing for anyone to do.

Wikidata _could_ become an interface for editing _any_ data and presenting changes to the author of that data, by showing the diff or change log of edits. This would position them as a sort of campaign for better collaboration.

It's hard to tell how a list has been edited on Wikidata, at least with the tools most people have. Because lots of lists aren't accessible by addressable identifiers it's hard to track changes over time between 'forks' of the data, and there doesn't seem to be a pattern for merging back upstream.

Presenting changes to data is more complicated than presenting changes to code, partly because the size can make test diffs almost useless. Showing a summary of differing rows or enumerations could be useful.

## Useful ways to show changes to lists

What are they? Diff useful for small lists, but not for the BAN. Let's put aside worries about poor identifiers and assume we have two lists with high quality IDs that can't have duplicates (because they're semantic to the data contained in the list – see DC election IDs).

You need to show:

* Row level additions to each
* Row level deletions to each
* Field level changes

Does each row need a modified date as a way of deciding how to resolve conflicts?



## Random list analyser tool

Take a list, look for values in each column that are repeated but not too rare. Suggest they could become an enumeration – highlight similar values in case of error.

Who would the user for this be? Making more commodity the work of a developer or "data scientist" (whatever that means).

OpenRefine does this and is _ok_ to use for someone who can use a spreadsheet.


## On enumerations

By enumeration I mean a _value_ in a list that is spun off in to its own list and then linked to from other lists.

When you make an enumeration you are asserting that the _thing_ you're enumerating will usefully fit in to one or more defined boxes. Usefully is domain specific, not global.

Ref: YNR joint parties vs the list of registered parties.

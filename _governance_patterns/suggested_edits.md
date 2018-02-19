---
title: "Suggested edits"
layout: post
short_desc: "The ability to do the work of making a change and submit it to the governance system"
category: pattern
---

## Strengths


## Weaknesses


## Discussion

More advanced than error reporting is the ability to do the work of making a change and submit it to the governance system that control the list.

## Appropriate for

*

## Examples

* Local Authorities

#### Case study


GitHub Pull Requests or are a form of this and can be seen in action on [this pull request to the DCLG register of local authorities in England][local_auth_eng]:

> Birmingham District Council changed its name to Birmingham City Council
on 1st July 1986, not 1st July 1996. Birmingham District Council came
into existence in 1974.
>
> [Source](http://web.archive.org/web/20160319081846/http://www.birmingham.gov.uk/cs/Satellite?c=Page&childpagename=SystemAdmin%2FCFPageLayout&cid=1223092734590&packedargs=website%3D4&pagename=BCC%2FCommon%2FWrapper%2FCFWrapper&rendermode=live)

With the change getting accepted:

> I have been in touch with the custodian for this register, Stephen McAllister, Department for Communities and Local Government, who has checked source data, validated your correction and approved the change to the register.
>
> Our Open Registers Platform Team will now need to implement the correction as soon as possible to make the change you have brought to our attention. We work in the open and your feedback is a good example of the benefits that this brings in striving to maintain the integrity and accuracy of our register data especially as in this case, where there needs to be a correction.


However in this case the interface for suggesting an edit is limited to people who can use GitHub and can actually find the data. There is no link from the [register page](https://local-authority-eng.register.gov.uk/) to the GitHub repository that contains the data, and no documentation that explains this process is possible.

<!-- TODO who does this well? -->

[local_auth_eng]: https://github.com/openregister/local-authority-data/pull/16

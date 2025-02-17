---
title:  Content Publishing Checks
sidebar: bssw_sidebar
permalink: bssw_content_publishing.html
---


## What is this document?
This is a review checklist for all content that goes on the BSSw site.

## When should one use it?
This document provides a list of checks to be performed (1) when a new content idea is submitted, (2) when the content is in review stage before publishing. Please note that the [BSSw.io Content Board](https://github.com/betterscientificsoftware/bssw.io/projects/3) has various phases, as mentioned below. 
* Ideas backlog
* Topic review - Some preliminary checks need to be performed by the EB editorial team when the idea/topic is submitted.
* Ready to write
* Item progress
* Item review - Checks need to be performed by the shepherding EB member when the item is in review stage.
* Ready to publish
* Done

## What are Topic review Checks?
* Is the proposed content in scope for BSSw?
* Would the proposed content "fit" with existing content? (e.g.,  should it be a revision to or merger with am existing article rather than a separate article?)

## What are Item Review Checks?
The following steps assume that the BSSw editorial team has already determined that the topic is appropriate scope for BSSw.io.

### Sensitivity Checks
* Confirm that the article is written as per the predetermined scope outlined during the “topic review” phase, or determine suggested revisions/clarifications.
* Gender neutrality - BSSw.io article prefer to be gender neutral.
* Article tone - BSSw.io articles prefer to be polite and not offend any sensibilities of our intended audience 
* Review for sensitive information.
* PI approval  - if an original article talks about anything that can be construed as sensitive information and may need PI approval
* Image copyright permissions.
* Licensing terms checked on BSSw.io: "By checking this box, author acknowledges and agrees to licensing terms of content they publish at BSSw.io".
* Additional professional proofreading needed?

### Style/formatting Checks
* Adheres to the style guide for the specific content.
* Logo/image formatting - Please check for this unless style guide is specific instructions.
* Grammar, punctuation, spelling, syntax.
* Hyperlinks validity.
* Check for any prior versions of the same content. If the prior version is very outdated, consider replacing it with this newer content. Please judge on a case-by-case basis.
* Past events of the same conferences/workshops/etc. are not deleted and just kept as archives.
* If using [formal citations/references](bssw_styling_originalarticles.html#citationsreferences), use [`wikize_refs.py -i <base>.md`](https://github.com/betterscientificsoftware/bssw.io/blob/master/utils/README.md#wikize_refspy) to deal with these (see [here](https://github.com/betterscientificsoftware/bssw.io/blob/master/Articles/Blog/ReferencesInMarkdownHybridApproach.md) for details).

### Pre-publishing Checks
* Finalize the topic(s) and other parameters in metadata.
* Ensure [`wikize_refs.py -i <base>.md`](https://github.com/betterscientificsoftware/bssw.io/blob/master/utils/README.md#wikize_refspy) is run and commit (if `wikize_refs.py` is being used).
* Add the `preview` label to the PR (so PR branch will merge to 'preview' branch which is used to generate preview site).
* Update and sanity check on preview site to confirm overall display.
* Ensure that "publish: yes" in metadata before merging the PR to 'master'.

{% include links.html %}

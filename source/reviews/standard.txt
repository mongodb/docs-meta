======================
The Standard of Review
======================

.. _pr-standard:

Purpose
-------

The primary purpose of a review is to make sure that the overall health of MongoDB's
corpus is improving over time. All of the tools and processes of review are
designed to this end.

In order to accomplish this, a series of trade-offs have to be balanced.

First, authors must be able to **make progress** on their tasks. If you never
submit an improvement to the corpus, then the corpus never improves. Also,
if a reviewer makes it very difficult for *any* change to go in, then authors
are disincentivized to make improvements in the future.

On the other hand, it is the duty of the reviewer to make sure that each
PR is of such a quality that the overall content health of their corpus
is not decreasing as time goes on. This can be tricky, because often,
content degrades through small decreases in content health over time,
especially when a team is under significant time constraints and they feel
that they have to take shortcuts in order to accomplish their goals.

Also, a reviewer has ownership and responsibility over the code they are
reviewing. They want to ensure that the corpus stays consistent and maintainable.

The Prime Directive
-------------------

In general, reviewers should favor approving a PR once it is in a state
where it definitely improves the overall content health of the area
being worked on, even if the PR isn't perfect.

That is **the** paramount principle among all of the review guidelines.

There are limitations to this, of course. For example, if a PR adds content
that the reviewer doesn't want in their corpus, then the reviewer can certainly
deny approval even if the content is well-designed. Only Lead/Staff have this
ability to deny approval.

A key point here is that there is no such thing as "perfect" content; there is
only *better* content. Reviewers should not require the author to polish every tiny
piece of a PR before granting approval. Rather, the reviewer should balance out
the need to make forward progress compared to the importance of the changes they
are suggesting. Instead of seeking perfection, what a reviewer should seek is
*continuous improvement*. A PR that, as a whole, improves the maintainability,
readability, and understandability of the corpus shouldn't be delayed for days
or weeks because it isn't "perfect."

Reviewers should *always* feel free to leave comments expressing that something
could be better, but if it's not very important, prefix it appropriately and move on.

.. important::

   Nothing in this document justifies checking in PRs that definitely
   **worsen** the overall content health of the corpus. The only time you
   would do that would be in an emergency.

Mentoring
---------

Reviews have an important function in teaching authors something new. It's
always fine to leave comments that help an author learn something new. Sharing
knowledge is part of improving the content health of a corpus over time.

Principles
----------

- Technical facts and data overrule opinions and personal preferences.

- On matters of style, the :ref:`style guide <documentation-style-guide>`
  is the absolute authority. Any purely style point (whitespace, gerunds, etc.)
  that is not in the style guide is a matter of personal preference. The
  style should be consistent with what is there. If there is no previous style,
  accept the author's.

- **Aspects of authoring are almost never a pure style issue or just a personal preference.**
  They are based on underlying principles and should be weighed on those principles,
  not simply by personal opinion. Sometimes there are a few valid options.
  If the author can demonstrate (either through data or based on solid principles)
  that several approaches are equally valid, then the reviewer should accept the
  preference of the author.

- If no other rule applies, then the reviewer may ask the author to be
  consistent with what is in the current corpus, as long as that doesn't
  worsen the overall content health.

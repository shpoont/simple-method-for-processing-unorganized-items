# Decision log

This is the repository's dedicated record of lasting decisions and their
reasons. The [method](simple-method-for-processing-unorganized-items.md)
contains the guidance to use; the [changelog](../CHANGELOG.md) records versioned
changes and repository maintenance.

## D01 — 2026-10-09: Maintain a shared method independently of implementations

**Status: adopted.** Maintain one essential, human-readable method for people
and agents, using generic concepts. Emails, files, folders, notes and work items
are examples rather than the method's organizing structure.

Give the method a canonical repository separate from Organizers and other
implementations. Version the method independently so implementations can pin a
released baseline without coupling its development to a particular integration.

## D02 — 2026-10-09: Preserve the initial method baseline

**Status: adopted.** The initial method is v1.0.0 at commit
`20fea620e8157cc20ada5ab2da2c4edd6c2f0b68`. Published annotated tags are fixed;
changes to the method require a new version.
Repository maintenance alone does not require a method release.

A completed document and illustrative checks do not establish practical
effectiveness. Claims about use or implementations require evidence from that
work.

## D03 — 2026-10-09: Prepare public distribution using PEM's repository conventions

**Status: adopted.** The owner requested preparation for public release using
the Project Execution Model repository as the reference, then authorized public
visibility after verification. Preserve the method file byte-for-byte.

Use a README for navigation, licensing, feedback and disclaimers; keep the method
and this decision log in `docs/`. Apply the MIT License, including to the initial
method. Use relevant repository topics and PEM's collaboration settings.

These changes support distribution and maintenance. They do not revise the
method or establish its practical effectiveness. Preserve the v1.0.0 tag and its
original file layout so existing pins remain valid.

## D04 — 2026-10-09: Remove the dedicated versioning document

**Status: adopted.** The owner requested removal of `VERSIONING.md`. Remove the
document and its navigation links. Retain the method baseline and fixed tags;
the method itself is unchanged.

## D05 — 2026-10-10: Make scope refinement and handling more practical

**Status: proposed for v1.1.0.** The owner agreed the direction discussed in
[issue #1](https://github.com/shpoont/simple-method-for-processing-unorganized-items/issues/1)
and requested a method revision on a branch and PR, using a team of subagents.
This revision changes the method; the published v1.0.0 baseline remains fixed.

Practical usefulness guides the revision. Explain the collection, current scope
and action targets through useful examples, while retaining the existing loop
and generic concepts. Examples should help readers see what they can do without
creating mandatory phases or limiting discovery to browsing and searching.

Prefer scope refinement toward one appropriate shared handling action. A likely
action helps focus selection but remains provisional. Dependencies or a shared
result can justify considering items together even when several actions are
needed. The final decision may change the recommendation, target subsets, or
contain several actions within the same scope. Review and approve the final
actions and targets when approval is required.

Investigation can improve either membership or handling decisions. Judge its
effort by the expected improvement, consequences of error, time and resource
cost, available evidence and usefulness for later work. Item count alone is not
a sufficient rule. Evidence outside the collection provides context without
expanding membership or authority to change that source.

Collection boundaries do not require a complete inventory. By default, order
the eligible items discovered so far. When strict order across the whole
collection matters, require evidence that establishes it; a reliable sorted
view can suffice. Preserve truthful coverage claims and the distinction between
a container action, fulfilled handling of included contents and individual
inspection.

Document reviews and paper walkthroughs, recorded in the
[revision review](reviews/v1.1.0-review.md), support the clarity of this revision.
They do not establish its practical effectiveness in real use.

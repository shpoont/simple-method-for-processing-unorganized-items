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

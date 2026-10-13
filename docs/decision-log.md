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

**Status: adopted for v1.1.0 on 2026-10-11.** The owner agreed the direction
discussed in
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

Collection boundaries do not require a complete inventory. Use the collection's
existing order or current view by default. Choose a different order when the
purpose requires it, or a useful order when none is available. Selection can use
discovered eligible items unless strict order across the whole collection is
required. In that case, require evidence that establishes the order; a reliable
sorted view can suffice. Preserve truthful coverage claims and the distinction
between a container action, fulfilled handling of included contents and
individual inspection.

Document reviews and paper walkthroughs, recorded in the
[revision review](reviews/v1.1.0-review.md), support the clarity of this revision.
They do not establish its practical effectiveness in real use.

## D06 — 2026-10-10: Make the reading path and examples explicit

**Status: adopted for v1.1.0 on 2026-10-11.** A compact document can still be
difficult to follow when instructions, explanations, examples and exceptions are
interwoven.
Give each step a clear practical instruction and keep the existing procedure
visible. Make defaults and optional choices easy to recognize, with conditions
placed beside the instruction they qualify.

Use the established method terms in shared rules. Clearly label concrete
examples so readers can immediately distinguish an illustration from generic
guidance. Keep useful examples that show possible activities and decisions.
Explain collection membership and included container contents in plain language.
Using an existing order should not require an additional setup decision.

Define the established terms in a short terminology section before the
procedure, so readers can find their meanings in one place. Explain item,
container, collection, scope, handling decision, action, action targets, results
and processed. Keep the steps focused on what to do, with the same meanings
throughout.

Preserve all agreed method behavior and safeguards while improving the reading
flow. Fresh model reviews can support a revision, but they do not establish the
owner's acceptance of its readability.

## D07 — 2026-10-10: Clarify continuation and completion for the final candidate

**Status: adopted for v1.1.0 on 2026-10-11.** The owner requested a final revision
using the external feedback and another iteration of subagents before version
release. The final candidate was prepared on the existing PR. The owner accepted
it and requested release on 2026-10-11.

An empty current view does not establish completion of the defined collection.
Continue discovery within the boundary and work limit when authorized work can
proceed, unless evidence already establishes completion. Keep unfinished items
accessible and recoverable when actions change their location or remove them
from the view.
No traversal algorithm or complete inventory is required.

A scope is processed only when verified chosen handling covers every member.
Successful handling of a subset completes that subset; omitted or unfinished
members stay unprocessed. Evidence can cover a group or container collectively,
without individual inspection or enumeration. Verified summaries, deliberate
non-action and accepted follow-up arrangements remain valid handling.

When a recommendation is useful, prefer one appropriate handling action. Keep
recommendations optional and show known exceptions and necessary combinations.
The preference does not limit justified recommendations or final decisions to
one action, require splitting, or replace action-directed scope refinement.

Trim repetition and consolidate illustrations where it helps readers follow the
procedure. Retain the requested terminology section and useful examples, with
concrete source terms explicitly labeled. Clarity and practical usefulness take
priority over a fixed word count. Record fresh reviews and the final snapshot;
retain earlier reviews as historical evidence rather than tests of new text.

## D08 — 2026-10-11: Prepare focused clarifications for the next revision

**Status: adopted for v1.2.0 on 2026-10-12.** The owner agreed the direction
discussed in
[issue #3](https://github.com/shpoont/simple-method-for-processing-unorganized-items/issues/3)
and requested a candidate on a branch and PR. After the recorded subagent and
Pro reviews, the owner accepted the candidate and requested release on 2026-10-12.

Keep the revision small. Briefly explain the shared method's meanings and
responsibilities, specialized handling and evidence for a domain, purpose or
recurring situation, and implementations that carry out those choices. These
roles may be combined, and direct simple use needs no separate specialization
document.

Replace the blanket requirement to resolve the previous outcome before every
retry with safe repetition and resolution where needed. Retain applicable
authority, conditions, verification and results that still apply.

Connect handling decisions to the purpose and require adequate evidence for
claims that its required results were achieved. Reconsider affected work,
including processed items, when relevant new information calls earlier handling
into question; retain results that remain valid. This does not require permanent
monitoring or erase valid historical results.

Make execution in parts explicit without adding another glossary term.
Preserve required order, dependencies, shared-result checks and verified chosen
handling for every included member before whole-scope completion.

Retain existing effort and reuse guidance, provisional single-action preferences,
ordering defaults and exceptions, authority, targets, conditions, effects,
accepted follow-up and accessible unfinished work. Detailed identity, traversal,
cost and tool strategies mainly belong in specialized methods and implementations.
Broader assurance policy, an additional stopping rule and a companion guide are
deferred unless a concrete need or gap appears.

The candidate does not change published baselines or establish practical
effectiveness. Its clarity and consistency can be reviewed before adoption;
evidence of benefit in actual use remains separate.

On 2026-10-12, a fresh review cycle found no consequential regression in the
five agreed clarifications. The owner requested three wording refinements:
explain working from discovered items, make required selection and action order
explicit, and describe how follow-up will reliably be picked up or reconsidered.
The refinements preserve the existing defaults, responsibilities and completion
claims. The [review record](reviews/issue-3-review.md) distinguishes the reviewed
snapshots and records a separate assessment of readability; any further
rearrangement remains a proposal.

Later on 2026-10-12, the owner requested the readability improvement. Retain the
existing instructions while separating the grouping preference from decisions
about keeping or splitting a group. Give scope refinement a clear signpost after
the statement that one item is enough. In Act and check, keep comparison and
completion guidance together, show applicable follow-up acceptance before
completion, and group changes and retries separately. Recoverability and access
to unfinished work continue to apply throughout. Subheadings organize the
existing guidance within the workflow; they do not add required stages or change
its conditions. Fresh readers and an independent comparison assess this
candidate arrangement before adoption.

The owner subsequently requested a fresh subagent review for unexplained
references and context that readers had not yet been given. Introduce the file
and email settings before their details, identify Downloads as an example folder,
and reconnect later examples before referring to their files or counts. Name the
collection as the boundary for outside material, consistent with D04. Identify
the process responsible for follow-up before requiring it to accept the work,
and use plain wording for an existing way to do so. Clarify the introductory
references to specialization and implementation. These contextual repairs retain
the method's rules, terms and workflow; they add no required stages or definitions.

The final Pro review found no material release blockers in the 1,298-word
candidate. It recommended two nonblocking clarifications about unsupported
completion and retry safety, and an optional deletion of the separate-view
sentence. The owner then accepted the current candidate for release. v1.2.0
preserves that exact reviewed method; the suggestions remain review observations.
The release adopts the focused revision without adding the deferred policies or
companion guide. This acceptance is distinct from evidence of effectiveness in
actual use.

## D09 — 2026-10-12: Prepare the first canonical Mail specialization

**Status: adopted for Mail v1.0.0 on 2026-10-12.** The owner accepted the reviewed
Mail recommendation, requested fresh readability,
practical walkthrough and consistency reviews, then authorized a branch and PR
after those reviews and focused rechecks passed. The owner subsequently
authorized merge and publication under the independent release scheme.

Maintain canonical specializations in `docs/specialized-methods/`. Each identifies
its governing shared-method version and follows all that method's rules. A
logical conflict should prompt consideration of a shared-method change rather
than an overriding specialization rule. The shared method remains v1.2.0,
unchanged; Mail's own release tag and a fixed commit identify this first
specialization under the subsequent versioning agreement in D10.

Inbox processing toward inbox zero is the main Mail example. Filtered sets and
other chosen collections remain supported. Distinguish common handling from
optional platform features, define membership meanings and time, and preserve
unfinished handling when messages leave their original view.

Handling can involve external systems. Keep actual targets, authority and
required results clear, including task updates, notifications and accepted
follow-up. Distinguish draft preparation, sending, responses and downstream
resolution. Relevant context, preferences and continuity between rounds support
handling without mandatory exhaustive investigation, priority setup or tracking
systems.

Organizers owns corresponding skill implementations, provider integration and
implementation checks. Each skill bundles deliberately approved copies of both
the specialization and its governing shared method, with source path, revision
and content hash for each. A combined reading copy can be assembled for
convenience. Implementation adoption and actual operations require their own
authority.

The development order is Mail, Files and folders, Generic Collections, then
Work Items. The [Mail review record](reviews/mail-specialization-review.md)
documents the consultations, reviews and paper cases. They support written
clarity and consistency; practical usefulness and installed behavior remain to
be established through implementation and use.

## D10 — 2026-10-12: Version each specialization independently

**Status: adopted with Mail v1.0.0 on 2026-10-12.** The owner agreed to independent
versions for the shared method and each specialization, requested the PR update
and durable `AGENTS.md` instructions, then approved publication.

Methods can evolve and be adopted at different rates. An improvement to Mail
does not require a new shared-method or unrelated specialization version. Do not
add another global version for the collection. Retain existing `vX.Y.Z` tags for
shared-method releases and use namespaced tags such as `mail/v1.0.0` for
specializations. Release titles and notes identify the affected method, even
though the tag captures a repository snapshot.

Keep the shared-method release marked "Latest" on GitHub and give specialization
releases explicit method titles. Multiple methods may be released from the same
commit using their own tags; separate permanent branches are not required.

Each specialization declares its own version and its exact governing shared
version, linking to the fixed released document. Review affected specializations
when the shared method changes. Adoption is deliberate and produces a new
specialization version; it does not silently change existing releases or require
matching version numbers. Specializations continue to follow their governing
shared rules, and implementations pin approved versions of both documents.

Record the concise version-change criteria in the [README](../README.md#versioning)
and maintenance instructions in [AGENTS.md](../AGENTS.md). Keep published tags
fixed and distinguish method changes from repository maintenance. Preserve
historical review evidence while recording the current candidate's metadata.

The first Mail release is v1.0.0, governing shared v1.2.0, under `mail/v1.0.0`.
The adopted revision adds the version declaration and fixed dependency link
without changing Mail handling guidance or the shared-method contents.
Method publication does not adopt an implementation or authorize actual mail
operations.

## D11 — 2026-10-13: Clarify handling authority and informed approval

**Status: direction agreed; shared v1.3.0 and Mail v1.1.0 candidates in review.**
The owner accepted both shared clarifications and requested a PR. Publication
remains pending.

Distinguish authority to carry out work from authority to choose its handling.
Keep existing authorized decisions, policies and delegated judgment usable;
resolve material uncertainty about who may choose before acting on the decision.
A clear authorized instruction, including a revision, can supply informed approval
when targets, material effects and conditions are understood. Revision alone
requires no additional confirmation; material uncertainty still needs clarification.

Use compatible minor versions. Mail's candidate adopts shared v1.3.0 without
changing Mail handling text. Published Mail v1.0.0 keeps its shared v1.2.0 pin.
The [review record](reviews/decision-authority-review.md) records the comparison,
candidate snapshots and publication requirements.

Interactive pacing belongs to implementations. Mail Organizer changes and
practical checks remain later work in Organizers, outside this repository's PR.

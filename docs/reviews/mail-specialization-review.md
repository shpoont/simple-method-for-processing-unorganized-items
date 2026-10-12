# Mail specialization review

Date: 12 October 2026.

Status: owner-accepted Mail v1.0.0 candidate, prepared for publication through a
branch and PR. Inclusion on main and tagged release remain pending. Organizers
dependency adoption, skill implementation and actual operations remain separate
work requiring authority.

## Governing method and publication candidate

The Mail specialization follows shared method v1.2.0 at commit
`7dfd40b5c24f41e40251724261ca4a495648096e`.
Its SHA-256 is
`7cbd280c52325c9ffdac563b54b3a0a457ab2bf7f5237d3777f701b237006440`.

The publication candidate is [Mail Processing v1.0.0](../specialized-methods/mail.md),
983 words. Its SHA-256 is
`1842d5f1e815990f930cb0799282642352d009f6c7eecdb318a4549f13a452ff`.

## Agreed requirements

- Inbox processing toward inbox zero is the main use case. Other chosen email
  collections, including filtered messages without labels, remain supported.
- Keep the specialization platform agnostic. Introduce and explain optional
  features where used, including what a label-based selection criterion means.
- Follow the main method's rules. Raise logical conflicts for consideration of
  a main-method change rather than introduce an overriding specialization rule.
- Version the shared method and each specialization independently. Declare both
  the specialization's version and its exact governing shared version; link to
  the fixed shared release and review compatibility before adopting another.
- This repository owns canonical specialized methods. Organizers owns their
  corresponding skills, provider integration and implementation checks.
  Skills bundle deliberately approved method revisions with source path,
  revision and content hash. The owner approves adoption and subsequent actions.
- Preserve practical, concise guidance, consistent terminology and examples
  that introduce their context before referring to details.

## Pro consultation

One consolidated Pro request supplied the complete released method and the
agreements above. The full composer text and all glossary lines were checked
before submission. The completed conversation readback also matched the request
after normalizing whitespace and rendered Markdown escaping.

Pro found no conflict or genuine gap requiring a shared-method change. It
recommended individual messages as items, with conversations providing context
or groups of eligible messages. It distinguished verified handling from mailbox
appearance, required meaningful filter boundaries, and placed provider effects
and tool evidence with implementations.

Its proposed defaults need no further policy choice before owner review:
individual-message items and bounded inbox-zero rounds are recommendations
within the proposal. Approval of the specialization and adoption into Organizers
remain separate decisions.

The original Pro draft was 836 words. Two wording clarifications produced the
initial 838-word recommendation:

- Replace "Choose the mailboxes" with "Choose the mail account or accounts" to
  distinguish account selection from folder or view selection.
- Replace authority "granted by the owner or applicable policy" with "the
  authority under which you are working" to avoid an unexplained owner reference.

These editorial clarifications were checked against the shared method; they did
not require another Pro exchange. The shared method was preserved byte-for-byte.

## Subsequent dependency agreement

After the Pro consultation, the owner agreed to keep canonical specializations
separate and reference their governing shared-method version. Brief repetition
may improve readability. Implementations bundle approved copies of both documents,
with source path, revision and content hash for each; a combined reading copy can
be assembled from those sources. This agreement is recorded in the
[folder introduction](../specialized-methods/README.md). At that point, the Mail
draft awaited owner review.

## Second Pro consultation: practical mail handling

The owner requested a further Pro discussion and draft update after reviewing
external-system actions and the
[OpenAI inbox guide](https://learn.chatgpt.com/use-cases/manage-your-inbox).
One consolidated request in the
[Review Processing Method conversation](https://chatgpt.com/c/6acb32a3-0960-83eb-a554-970564a159dc)
supplied the full current draft, shared method and six proposed clarifications.
Pro selection and the full composer text, including both tables, were verified
before sending. The final response was read after generation had completed.

Pro recommended short clarifications for all six points, within the existing
sections, and found no shared-method conflict or need for another stage:

- Handling can require actions outside mail, with explicit targets, authority
  and verified results. Creating a task record alone does not establish accepted
  follow-up.
- Relevant context can reveal changed or already fulfilled requests. Gathering
  that context remains conditional on its value; it does not expand the mail
  collection or authorize changes elsewhere.
- A checked, accessible draft can satisfy draft-only handling. Sending remains
  required when the decision calls for a sent reply.
- Waiting for another person can need a reliable review arrangement. That
  arrangement does not establish an actual response or resolution when required.
- Relevant preferences can guide handling and purpose-based ordering without
  requiring priority setup or overriding the shared method's ordering rules.
- Repeated rounds preserve unfinished handling and accepted follow-up, keeping
  those states distinct and reconsidering affected work on material change.

Integration details, scheduling mechanisms and cadence, reply style and report
format remain implementation or user choices. The guide's example settings are
not adopted as method rules. Pro recommended omitting additional subscription
and mail-rule examples from this version because the authority and effects
requirements already govern them.

The revised Pro document was 972 words. Three editorial clarifications produced
the saved 977-word recommendation:

- Add Jira and Slack as examples of the already introduced work-tracking and
  messaging systems in the connected Inbox example. These two additions make the
  owner's examples recognizable without assuming particular integration
  capabilities.
- Make lighter inspection conditional on adequate evidence, avoiding an
  unconditional reading of Pro's statement that exhaustive searches and reading
  every message or attachment are not required.

These clarifications were checked locally and were not submitted for another
Pro round. The shared method remains byte-for-byte unchanged.

## Fresh subagent review and focused rechecks

The owner considered the 977-word draft good enough, then requested the usual
readability, practical walkthrough and shared-method consistency reviews before
publication. Three fresh subagents independently read both documents in full,
without consulting prior reviews or chat context. Their work was read-only.
All reviewed the same frozen Mail snapshot, SHA-256
`91a0b385cedbd25bb1b46633de9b3bfcf7c7b9ad52ccc646202d4ba86d142501`,
and verified the governing shared-method hash above.

| Review | Result |
| --- | --- |
| Readability and context | No material findings. The flow, explicit shared-method dependency, defaults, optionality and example references were understandable. The compressed grouping sentence had an optional wording improvement. |
| Practical paper walkthroughs | All seven cases passed: bounded Inbox clearing with an excluded later reply; label-and-summary handling that leaves a filter; draft-only versus send-required work; accepted waiting through an existing routine; changed or already handled requests; external task, notification and draft results; and uncertain or interrupted actions resumed later. No material gaps were found. |
| Shared-method consistency | No conflict, weakened rule or accidental stricter rule was found. General rules can be inherited through the explicit dependency. An optional qualifier could clarify that result dimensions depend on the chosen handling. |

The coordinator adopted two small editorial changes:

- Introduce grouping guidance with "When grouping messages" and identify the
  shared method's provisional preference, exceptions and guidance on effort.
- Keep specifying intended results mandatory, while making the illustrative
  result dimensions explicitly conditional on the chosen handling.

The optional interrupted-send example was not added: the existing recovery and
safe-retry rules cover that case, and its paper walkthrough passed.

The readability and consistency reviewers then compared only the two changed
paragraphs and their necessary context. Both focused rechecks passed with no
repair needed. Grouping remains provisional, effort and exceptions remain
governed by the shared method, and all actually required results still need
specification and verification. The final reviewed snapshot was 990 words,
SHA-256 `7c953375679a48487cba2a0453f87d5b1200fa4fe71b2e624476aad6452e49c1`.
The shared method is unchanged. No further Pro consultation was needed.

These are document reviews and paper cases. They do not establish practical
effectiveness, provider capabilities or installed implementation behavior.

## Owner acceptance and publication preparation

After the reviews and focused rechecks passed, the owner authorized proceeding
with the branch and PR. At that stage, removing only the draft-status marker
produced a 982-word candidate; the remaining text was byte-for-byte identical to
the reviewed snapshot. Its SHA-256 was
`8815c7ff638e55c1bd7dd8b054c295500ac87aa70463f6f570df3312741ee6fd`.

The README, specialized-method index, changelog and D09 record this first Mail
specialization and its governing shared method. The shared method stays at
v1.2.0, byte-for-byte unchanged. No published tag is changed or new shared-method
release implied. The merged commit will provide a fixed Mail source revision.

## Independent versioning update

The owner subsequently agreed to independent specialization versions and
requested a PR update, repository `AGENTS.md` instructions and supporting notes.
Declare Mail v1.0.0 and replace its relative shared-method reference with a link
to the fixed v1.2.0 document. These are the only changes to the Mail candidate;
its handling guidance and the shared-method bytes are preserved. The current
candidate's 983-word count and hash are recorded above.

The README describes namespaced specialization tags and version-change criteria.
The index and changelog identify Mail as a release candidate, D10 records the
decision, and `AGENTS.md` gives maintenance instructions. Publication will use
`mail/v1.0.0`; no tag is created by this PR update.

Focused checks confirmed the exact metadata-only Mail change, the preserved
shared method, the fixed dependency target and consistent version declarations.
All 23 relative Markdown links resolve, and whitespace checks pass. The earlier
reviews remain evidence for the preserved handling text; no new Pro or subagent
review is implied.

## Written consistency checks

These checks assess the document's meaning; they do not establish real-use
effectiveness or provider behavior.

| Case | Reading supported by the recommendation |
| --- | --- |
| Inbox processing with later arrivals | Included messages can be handled and cleared while excluded new messages remain. A completed bounded round and an empty live inbox are separate claims. |
| Applying a label removes mail from a filter | Original eligibility and unfinished handling remain recoverable; a required summary still needs verification. |
| A conversation contains excluded messages | Those messages can provide context. Any action affecting them needs separate authority. |
| Existing policy supplies group handling | Adequate collective evidence can support handling without reading every message or inspecting every attachment. |
| The purpose requires a summary or deliberate non-action | Verified handling may leave processed messages present. An empty inbox is conditional on the chosen purpose. |
| A reply attempt has an uncertain outcome | Sending, receipt and resolution are distinct results. The inherited safe-retry rule governs repetition; confirmed valid results remain usable. |
| A message leads to work in another system | External targets and effects need authority and evidence. Every required task update, accepted follow-up, notification, draft and Inbox-clearing result remains part of the handling decision. |
| Sent mail or an existing task changes the decision | Relevant context can prevent duplicate work without becoming part of the mail collection. Investigation remains conditional on its expected value. |
| Draft-only handling versus a required sent reply | A checked, accessible draft can satisfy the former. It cannot silently replace sending or required acceptance of later review or sending. |
| Waiting for a response | An appropriate routine can accept follow-up when that is the chosen handling. It does not satisfy a decision requiring an actual response or resolution. |
| Preferences influence importance or order | Preferences may guide handling; the existing-order default and purpose-based exceptions remain governed by the shared method. |
| A subsequent round begins | Unfinished mail handling and accepted downstream follow-up remain distinct and accessible. A new boundary does not erase earlier obligations; material new information triggers reconsideration. |

The recommendation inherits ordering, optional investigation and recommendations,
action-directed grouping, effort judgment, authority and conditions, accepted
follow-up, execution in parts, whole-scope and shared-result completion,
reconsideration, recovery and stopping rules. It adds Mail-specific interpretation
and examples within the existing loop.

## Remaining work

Merge and publication remain pending. Organizers then considers adoption of the
approved revision and corresponding implementation work. Practical usability,
platform behavior and installed implementation checks remain to be established
through that work.

# Changelog

Versioned summaries of changes to the method and repository maintenance.
For lasting decisions and their rationale, see the
[decision log](docs/decision-log.md).

## Unreleased

### Shared method v1.4.0 candidate

- Allow starting with an item or a candidate group from an available overview,
  choosing and changing approaches according to available information and
  proportionate investigation.
- Distinguish the existing view as a starting point from required selection
  and action order. Preserve whole-collection ordering evidence.
- Apply effort guidance throughout the work, including execution and recovery.
- Align scope refinement and continuation with either starting approach.

### Mail v1.2.0 candidate

- Align scope selection and order with the shared v1.4.0 candidate and propose
  deliberate adoption of that governing version.
- Preserve all other Mail handling guidance.

These are compatible minor candidates under the README's criteria. Published
shared v1.3.0 and Mail v1.1.0 remain fixed. Mail's candidate reference is local
during review and must be pinned to the released governing source before
publication. See the [candidate review](docs/reviews/scope-selection-review.md).
Organizers implementation adoption and skill interaction changes remain separate.

## [Mail v1.1.0](https://github.com/shpoont/simple-method-for-processing-unorganized-items/releases/tag/mail/v1.1.0)

Released on 2026-10-13 after the owner accepted the reviewed revision and
requested publication.

- Adopt the fixed shared v1.3.0 document, preserving all Mail handling text.
- Keep the independent Mail version and tag; Mail v1.0.0 retains its original
  shared v1.2.0 dependency.

This compatible adoption uses a minor version under the README's criteria.
Publication does not update an Organizers skill or establish implementation
behavior. See the [release review](docs/reviews/decision-authority-review.md).

## [Shared method v1.3.0](https://github.com/shpoont/simple-method-for-processing-unorganized-items/releases/tag/v1.3.0)

Released on 2026-10-13 after the owner accepted the reviewed revision and
requested publication.

- Distinguish authority to choose handling from authority to carry out work.
  Keep choices within established authority and resolve material uncertainty
  before acting on the handling decision.
- Clarify informed approval: a clear authorized instruction, including a
  revision, can supply approval when targets, material effects and conditions
  are understood. Revision alone does not require another confirmation.
- Retain the existing loop, optional recommendations and scope view, authorized
  policies, flexible final decisions and completion rules.
- Fix historical review links to their released documents.

This compatible clarification uses a minor version under the README's criteria.
Published shared v1.2.0 and Mail v1.0.0 remain fixed. See the
[release review](docs/reviews/decision-authority-review.md).

## [Mail v1.0.0](https://github.com/shpoont/simple-method-for-processing-unorganized-items/releases/tag/mail/v1.0.0)

Released on 2026-10-12 after the owner accepted the reviewed Mail recommendation,
approved independent specialization versions and requested publication.

- Add the first platform-independent Mail specialization, with Inbox processing
  as the main example and support for filtered and other chosen collections.
- Explain external actions and context, draft-only handling, waiting for
  responses, relevant preferences and continuity between processing rounds.
- Establish canonical specialized methods in `docs/specialized-methods/`.
  List included methods and their versions directly in the main README.
  Organizers implements the corresponding skills and bundles approved copies of
  each specialization and its governing shared method with versions, provenance
  and hashes.
- Version each specialization independently of the shared method. Declare Mail
  v1.0.0 against the fixed shared v1.2.0 document, document the release convention,
  and add repository `AGENTS.md` guidance for maintaining versions and evidence.
- Record two Pro consultations, three fresh independent reviews, seven paper
  walkthroughs and focused rechecks with no material findings.

The shared method remains v1.2.0, unchanged. Mail v1.0.0 uses the independent tag
`mail/v1.0.0`. The GitHub release identifies Mail explicitly and leaves the shared
release marked "Latest". This addition does not create a new shared-method
version or adopt an implementation.

## [v1.2.0](https://github.com/shpoont/simple-method-for-processing-unorganized-items/releases/tag/v1.2.0)

Released on 2026-10-12 following the discussion in
[issue #3](https://github.com/shpoont/simple-method-for-processing-unorganized-items/issues/3).
The owner accepted the reviewed 1,298-word method and requested release.

- Briefly explain the shared method, specialized methods and implementations,
  preserving direct use without separate specialization documents.
- Allow safe retries under uncertainty while resolving the previous outcome
  where needed and reusing confirmed results that still apply.
- Connect handling decisions and claims of achieved purpose to the intended
  results and adequate evidence.
- Reconsider affected processed work when new information calls earlier
  handling into question, retaining results that remain valid.
- Make handling a scope in parts explicit while preserving required order,
  dependencies and verified completion for every included member.
- Clarify working from discovered items, required selection and action order,
  and how arranged follow-up will be picked up or reconsidered.
- Improve reading flow with a scope-refinement signpost, shorter grouping
  paragraphs, and clear topics for execution, follow-up, completion and recovery.
- Establish example settings and references before using their details; clarify
  material outside the collection and the process responsible for follow-up.

Fresh reviews, the readability assessment and the final Pro review are recorded in the
[issue #3 review](docs/reviews/issue-3-review.md).

Broader assurance policy, an additional stopping rule and a companion guide
remain deferred. The published v1.1.0 and v1.0.0 baselines remain fixed.

## [v1.1.0](https://github.com/shpoont/simple-method-for-processing-unorganized-items/releases/tag/v1.1.0)

Released on 2026-10-11.

- Distinguish the collection, current scope and action targets with practical
  examples, including multiple actions within one scope.
- Explain candidate discovery and membership assessment, with examples of
  searching, exploring, comparing and seeking context.
- Prefer scopes and useful recommendations centered on one appropriate handling
  action while preserving dependencies, known exceptions, necessary combinations
  and flexible final decisions.
- Explain how investigation supports both membership and handling, including
  evidence from outside the collection and judgment about worthwhile effort.
- Allow progress through large or nested collections without a complete map;
  distinguish order among discovered items from required collection-wide order.
- Use the collection's existing order by default and explain included items
  and container contents in plain language.
- Define the method's terms in a terminology section, use them consistently
  in shared rules, clearly label concrete examples, and organize the
  instructions around an easier reading path.
- Explain continued discovery when the current view runs out and keep
  unfinished items accessible and recoverable when actions change their location.
- Require verified handling covering every member before a scope is processed;
  omitted or unfinished members remain unprocessed.
- Preserve approval, verified handling, recovery, follow-up acceptance and
  honest reporting of coverage.

## Repository maintenance — 2026-10-09

- Add a README with navigation, author attribution, feedback guidance and
  disclaimers, following the Project Execution Model repository's conventions.
- Add the MIT License and a dedicated decision log.
- Move the method into `docs/` without changing its contents.
- Align repository topics and collaboration settings for public distribution.
- Retain method version v1.0.0 and its existing fixed tag.
- Remove `VERSIONING.md` and update the references to it.

## [v1.0.0](https://github.com/shpoont/simple-method-for-processing-unorganized-items/releases/tag/v1.0.0)

Released on 2026-10-09.

Initial release of A Simple Method for Processing Unorganized Items.

- Define collection boundaries, item order and included nested contents.
- Work through each scope: choose the scope, decide what to do, then act and check.
- Handle related-item groups, action approval, uncertain results and follow-up.
- Define when processing is complete and what zero means for a collection.

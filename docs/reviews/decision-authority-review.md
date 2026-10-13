# Decision authority and approval review

Date: 13 October 2026.

Status: approved for publication as shared v1.3.0 and Mail v1.1.0. The owner
accepted the reviewed revision in PR #6 and requested release.

## Scope and review basis

An independent Pro opinion and a focused wording proposal informed the discussion.
The owner accepted the authority distinction and informed approval for revised
instructions, requesting clearer wording for handling not already decided.
The coordinator reviewed the edited sections in context for readability and
consistency. No new independent review of the final files or implementation
test is claimed.

The shared method changes only the two agreed blocks and adds a version/status
line. Its loop, definitions, examples, scope refinement, optional recommendations
and scope view, effort guidance, completion and recovery rules are preserved.
Mail changes only its version/status and governing-source reference; every word
of its handling guidance is preserved.

## Written consistency checks

| Case | Reading supported by the reviewed revision |
| --- | --- |
| Authorized policy or delegated judgment supplies handling | Existing authority can supply a decision without a universal human-approval checkpoint. |
| Authority to perform work leaves the handling choice uncertain | Resolve the material uncertainty before acting on that decision; authorized preparation remains available. |
| A clear instruction revises handling for identified subsets | It can supply approval when targets, material effects and conditions are understood; revision alone needs no extra confirmation. |
| Targets, effects, conditions or authority remain unclear | Clarify material uncertainty before execution; a revised instruction does not waive independently required approval. |
| Some scope members remain pending or depend on a shared result | Existing whole-scope completion and accessible unfinished-work rules still apply. |
| Mail adopts the clarified shared method | Its existing authorized-handling and approval guidance follows the clarification without a domain exception. |

These are document checks. They do not establish practical effectiveness,
conversational behavior or provider correctness. Mail Organizer implementation
and practical checks belong to Organizers under separate authority.

## Candidate snapshots and preservation

| Document | SHA-256 |
| --- | --- |
| Shared v1.3.0 candidate | `7ff0b452a7cf104cba0c20815b7b6249d7599889436243f2ddb5b3d85e8e0cae` |
| Mail v1.1.0 candidate | `45e8e13a37dfac1aa34620c75d8d277a20f6b9a7f15d1ae8338114c1193c936e` |

Published shared v1.2.0 and Mail v1.0.0 retain their fixed tags, sources and
historical evidence. Historical review links point to those released sources
rather than the evolving documents.

At candidate review, exact comparisons confirmed the stated change boundaries
and preserved historical decision and release prose. All 28 relative Markdown
links and their anchors resolved, and whitespace checks passed. Candidate labels
and governing versions agreed across the documents, indexes, changelog and
decision record.

## Final release snapshots

| Document | SHA-256 |
| --- | --- |
| Shared v1.3.0 | `9c1dea27cc78b22679ca07cdb86fa2692da3cf0a300a151966f15da913213084` |
| Mail v1.1.0 | `8a8e30dae7eeaa1c89a9c6451c2ca25343f65bb3b105a999cae6f5c0ce5cfc4b` |

Finalization removes the candidate markers and fixes Mail's governing reference
to the released shared v1.3.0 source. Exact comparisons preserve all reviewed
handling guidance. Final relative links, anchors, whitespace and version
declarations are checked separately from the historical candidate evidence.

## Version and publication

Both minor versions follow the README's compatible-clarification rule.
Mail v1.1.0 deliberately adopts shared v1.3.0; the existing Mail v1.0.0 release
continues to follow shared v1.2.0. Unchanged Mail-specific text does not eliminate
the need for a new version when adopting another governing method.

The approved documents use independent `v1.3.0` and `mail/v1.1.0` release tags.
The shared release remains GitHub Latest and Mail uses `--latest=false`.
Publication does not update the Organizers plugin or authorize mail operations.

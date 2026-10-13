# Decision authority and approval review

Date: 13 October 2026.

Status: shared v1.3.0 and Mail v1.1.0 release candidates. The owner agreed the two
shared clarifications and requested a PR. Merge and publication remain pending.

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

| Case | Reading supported by the candidate |
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
rather than the evolving candidate.

Exact comparisons confirm the stated change boundaries and preserve historical
decision and release prose. All 28 relative Markdown links and their anchors
resolve, and whitespace checks pass. Candidate labels and governing versions
agree across the documents, indexes, changelog and decision record.

## Version and publication preparation

Both proposed minor versions follow the README's compatible-clarification rule.
Mail v1.1.0 deliberately adopts shared v1.3.0; the existing Mail v1.0.0 release
continues to follow shared v1.2.0. Unchanged Mail-specific text does not eliminate
the need for a new version when adopting another governing method.

The candidate Mail reference points to the explicitly versioned shared candidate
in this branch. Before publication, finalize both candidate labels and release
records, and replace that reference with the fixed released shared v1.3.0 source.
Publish the approved snapshot under independent `v1.3.0` and `mail/v1.1.0` tags;
the shared release remains GitHub Latest and Mail uses `--latest=false`.
Publication does not update the Organizers plugin or authorize mail operations.

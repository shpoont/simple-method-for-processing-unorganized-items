# Repository guidance

## Canonical documents

- The shared method is `docs/simple-method-for-processing-unorganized-items.md`.
  Specialized methods live in `docs/specialized-methods/` and follow their declared
  shared-method version. Raise logical conflicts for consideration of a shared
  method change rather than override its rules in a specialization.
- This repository owns method documents. Organizers owns corresponding skills,
  platform integration and implementation checks. Document changes do not by
  themselves adopt or update an implementation.
- Keep release conventions in [README.md](README.md#versioning), changes in
  [CHANGELOG.md](CHANGELOG.md), and lasting decisions and reasons in
  [docs/decision-log.md](docs/decision-log.md). Do not recreate `VERSIONING.md`.

## Version maintenance

- Version the shared method and each specialization independently. Existing
  `vX.Y.Z` tags identify shared-method releases; specialization tags use a stable
  method name, such as `mail/v1.0.0`. There is no additional global version.
- Each specialization declares its own version and its exact governing
  shared-method version, with a link to that released document. Keep the existing
  declared dependency until a reviewed update is explicitly adopted. Assess
  affected specializations when the shared method changes; do not automatically
  bump their versions or change their dependencies.
- Follow the version-change criteria in the README. Changes to a released method
  document, including adoption of another governing version, require a new
  version of that method. Repository maintenance alone does not. Keep published
  tags and baselines fixed.
- Update the affected version declaration, index, changelog, decision and review
  records together as applicable. Clearly distinguish a release candidate from
  a published release. Release titles and notes identify the method being
  released even though a Git tag captures the repository snapshot.
- Keep the shared-method release marked "Latest" on GitHub. Create specialization
  releases with an explicit method title and `--latest=false` so independently
  versioned methods do not compete for that label.

## Editing and verification

- Keep guidance practical and concise. Introduce terminology and example
  settings before referring to their details. Preserve methods outside the
  agreed change; metadata work must not silently change handling rules.
- Preserve historical review snapshots and hashes. Record later changes and
  verify the current candidate separately; earlier reviews do not establish
  practical effectiveness or installed behavior.
- Before committing, check changed Markdown links, whitespace, version and
  dependency consistency, and any required preservation of method contents.
  Scale further review to the actual change.
- Before reporting a PR update as pushed, verify its remote head and files and
  the local working-tree state. Keep merge, release and implementation adoption
  claims tied to the actions actually completed.

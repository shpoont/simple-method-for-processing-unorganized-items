# Method Versioning

Versions identify the method, independently of organizer implementations.
Use `vMAJOR.MINOR.PATCH` for annotated Git tags and matching GitHub releases.

## Choosing a version

- **Major:** Change requirements so that readers or implementations must change
  their behavior.
- **Minor:** Add compatible guidance while preserving existing required behavior.
- **Patch:** Correct wording or formatting without changing meaning.

Every change to the method belongs in a new version. Repository maintenance alone
does not require a method release. Published tags are fixed; corrections require
a new version.

Implementations should pin a released tag or commit rather than follow `main`.

## Publishing a release

1. Update the method and add a dated entry to `CHANGELOG.md`.
2. Review the changes, commit them and push to `main`.
3. Create an annotated tag for the version on that commit and push the tag.
4. Publish a GitHub release for the existing tag, using the changelog entry as
   release notes.
5. Verify that the remote tag and release identify the intended commit and method.

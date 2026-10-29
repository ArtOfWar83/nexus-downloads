# Nexus downloads

This is where the Nexus installer, the Nexus Operator Manual and the Nexus release notes are kept.

Status: DRAFT and PRIVATE. Nothing here is public yet. Before this repository or any file in it is made public, the wording needs Kleinfeld's clearance and Arthur's own go.

## Layout

- `app/` : the signed and notarized Nexus installer (.dmg) goes here as a GitHub Release asset, one release per build. Not added yet.
- `manual/` : the Nexus Operator Manual PDF, one file per build, with its SHA-256.
- `release-notes/` : one Markdown file per build, named `NEXUS_<build>_release_notes.md`.
- `CHECKSUMS.md` : the SHA-256 of every published file.

## Rules

- Every file is added only after Kleinfeld has cleared its exact SHA-256 and Arthur has given his own go on that hash.
- A published file is never edited in place. A change is a new version with its own clearance.
- Write the name as "Nexus", plain.

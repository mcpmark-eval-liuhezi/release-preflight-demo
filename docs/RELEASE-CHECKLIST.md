# Release Checklist

A short, repeatable preflight pass to run on release day before shipping anything.

## Release day checklist

- [ ] **CI green** — all required checks pass on the default branch (CI, tests, lint, build)
- [ ] **Tag pushed** — release tag (`vX.Y.Z`) created and pushed to the repository
- [ ] **Release notes updated** — `RELEASE_NOTES.md` (or the GitHub Release description) reflects this version's changes
- [ ] **CHANGELOG updated** — user-visible changes, bug fixes, and breaking changes are documented
- [ ] **Docs in sync** — README and any docs touched by this release are up to date
- [ ] **Sign-off recorded** — the "Release readiness tracker" issue has been reviewed and signed off

## Gate

Ship only when every box above is checked. If any item fails, abort the release, fix, and restart the preflight pass.

# Contributing

Tantal is hardened Android firmware based on GrapheneOS. There is no fixed
plan, so open an issue before any change larger than a small fix.

## Before you start

- A security vulnerability is reported privately, see `SECURITY.md`. Never
  in a public issue.
- If a bug also reproduces on stock GrapheneOS, say so in the issue; we take
  it upstream. Don't report Tantal bugs to GrapheneOS: the project is not
  affiliated with us and does not support Tantal.

## Rules

- English everywhere: code, comments, docs, commit messages. Localization
  files are the only exception.
- Never weaken a GrapheneOS protection: verified boot, the locked
  bootloader and the rest.
- Don't remove GrapheneOS code; change behaviour through defaults and
  overlays.
- A new privileged permission or platform change needs an entry in the
  decision log.
- No signing keys or anything that looks like a secret in a commit.

## Pull requests

- One logical change per pull request, rebased on the main branch.
- Say what changed, why, and how you tested it (device and build).
- Your contribution is licensed under the `LICENSE` of the repository it
  goes into.

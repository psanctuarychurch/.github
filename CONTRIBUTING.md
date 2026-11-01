# Contributing

> **Joined the organization?** Start with [`ONBOARDING.md`](./ONBOARDING.md): two-factor login, connecting your AI helper, and how we work.


This file is the default contributing guide for any repository under the `psanctuarychurch` organization that
doesn't have its own `CONTRIBUTING.md`.

## Before you contribute

These projects belong to a church whose sacrament and practice are sacred and, for many members,
deeply personal. Please approach content (not just code) with that in mind:

- Never post personal information about members, ceremonies, or anyone's practice in an issue,
  pull request, or commit, even if it seems harmless.
- When you're unsure whether a change to wording or content is appropriate, open an issue and ask
  first instead of submitting a pull request.

## How to contribute

1. A small fix (a typo, a broken link) can go straight to a pull request.
2. For anything larger, open an issue first so it can be talked through.
3. Keep each branch to one change, and say *why* in the commit message, not just what changed.

## Commit titles: Gitmoji

Every commit subject starts with one gitmoji and a type, then a short subject in plain words:

```
:memo: docs(profile): the welcome deck linked from the profile
:sparkles: feat(decks): a new slide for newcomers
:bug: fix(links): the reading room's address
```

The twelve the fleet uses, and why the `:alias:` form, are in
[GITMOJI.md](https://github.com/drasticstatic/my-template/blob/main/GITMOJI.md). The local hook only warns; nobody
ever needs `--no-verify`. Pull requests merge with a merge commit, never squash, so every author's name survives.

## Reporting problems

Security issues go through [`SECURITY.md`](./SECURITY.md), not a public issue. Anything else is
welcome as a regular GitHub issue. Questions about the church itself are best sent to
[info@psanctuary.org](mailto:info@psanctuary.org).

## Questions

This organization is just getting started, and this guide will get more specific as its projects
grow. If something here doesn't fit, ask.

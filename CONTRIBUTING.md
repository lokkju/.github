# Contributing

This guide covers every repository owned by @lokkju that doesn't have a CONTRIBUTING.md of
its own.

## License

The default license for these projects is the
[PolyForm Shield License 1.0.0](https://polyformproject.org/licenses/shield/1.0.0/). A
repository whose LICENSE file names a different license is under that license instead.

## Issues

Search the open and closed issues first. To open a new one, pick the bug report or the
feature request form and fill in what it asks for.

Don't report a security problem in an issue; [SECURITY.md](SECURITY.md) says how to report
one privately.

## Pull requests

- Open an issue before starting anything bigger than a small fix, so the approach is agreed
  before you spend time on it.
- Branch from the default branch and keep each pull request to one change.
- Write commit messages and the pull request title as
  [Conventional Commits](https://www.conventionalcommits.org/) (`fix: ...`, `feat: ...`,
  `docs: ...`).
- Run the repository's tests and linters before you push, and update its docs when you
  change how something behaves.
- Commits, the pull request title and the body must not carry attribution to an AI tool:
  no `Co-authored-by:` trailer naming an AI assistant, no "Generated with" lines and no
  links to an AI session. Repositories that require the `no-ai-attribution` check refuse a
  pull request that has any of them.

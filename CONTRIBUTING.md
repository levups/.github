# Contributing

Thank you for helping. These gems are maintained by Level UP Solutions, two developers who use them in production
every day: small, focused pull requests get reviewed fastest.

## Before you start

- **Bugs**: open an issue with the smallest input that reproduces it. Most of our gems replace another one
  (Prawn, Slim, browser): when the output differs from that gem's, say so and show both.
- **Features**: open an issue first, so we can agree on the scope before you write the code. Being a drop-in
  replacement comes first: a feature that changes what existing code renders or returns stays off by default.
- **Security issues** never go in a public issue: see [SECURITY.md](SECURITY.md).

## Pull requests

- The repository's README says how to run its tests, its corpus and its benchmarks. CI runs the same.
- A bug fix comes with a test that fails without it; a new behaviour with tests of its own.
- A performance change states its numbers (before, after, Ruby version, with and without YJIT) and proves the
  output did not change.
- One change per pull request. Add a line to `CHANGELOG.md` when the repository has one.

Using an AI assistant is fine, as long as you have read and understood every line you submit and answer the review
yourself. Say so in the description.

By contributing, you agree that your work is released under the repository's license, and to follow our
[code of conduct](CODE_OF_CONDUCT.md).

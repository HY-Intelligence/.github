# Contributing

Thank you for contributing to HY-Intelligence repositories.

Repository-specific instructions take precedence over this document when present.

## Branches

Use `main` as the default integration branch unless a repository explicitly documents another policy.

Prefer short-lived branches with descriptive names, for example:

- `feat/<topic>`
- `fix/<topic>`
- `docs/<topic>`
- `refactor/<topic>`
- `research/<topic>`

## Changes

Keep each change focused on one coherent purpose. Preserve existing public contracts unless the change intentionally versions or migrates them.

For architecture or contract changes, document:

1. the problem being solved,
2. the ownership boundary affected,
3. alternatives considered when relevant,
4. compatibility or migration impact,
5. validation evidence.

For performance-sensitive changes, prefer measured evidence over assumptions and record the measurement scope and environment.

## Pull requests

Before opening or merging a pull request:

- run the repository's documented tests and validation commands,
- update documentation when behavior or contracts change,
- avoid unrelated formatting or refactoring noise,
- verify that no credentials, customer data, private paths, proprietary imagery, or other sensitive material are included,
- describe remaining limitations rather than presenting unverified work as complete.

## Commits

Use concise imperative commit messages that describe the intent of the change. Separate unrelated changes when doing so improves reviewability or rollback safety.

## Experiments and PoCs

Experimental repositories should preserve enough information to reproduce the claim being tested: inputs or synthetic substitutes, configuration, code revision, procedure, metrics, and known limitations. Do not silently move experiment-specific assumptions into reusable runtime code.

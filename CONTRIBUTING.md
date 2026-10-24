# Contributing

Contributions are welcome. Keep changes focused, explain why they are needed, and make sure they are ready for review.

## Branches

Keep `main` releasable. Submit changes through short-lived branches, one per logical change.

Use the following naming convention:

```text
<type>/<short-description>
```

Supported types: `feat`, `fix`, `chore`, `docs`, `test`, `refactor`, `ci`, `perf`.

Delete branches after merging.

## Commits

Use the following format:

```text
<type>(<scope>): <summary>
```

The scope is optional and, when specified, must match a Rust crate in the repository.

- Write the summary in the imperative mood, in lowercase, without a trailing period.
- Keep the summary within 72 characters.
- Explain why the change is needed in the body, not what it does. Wrap the body at 72 characters.
- Mark breaking changes with `!` after the type or scope, and include a `BREAKING CHANGE:` footer.

Examples:

```text
docs: clarify installation instructions
feat!: remove deprecated endpoint
```

## Pull requests

Keep each pull request focused on one logical change.

Before requesting review:

- Complete the implementation and relevant documentation.
- Run the relevant tests and checks.
- Describe the change, why it is needed, and how it was verified.

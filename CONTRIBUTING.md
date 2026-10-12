# Contributing

Thanks for taking the time. These are the defaults for every repository under
[@Nadimul96](https://github.com/Nadimul96); a repository's own `CONTRIBUTING.md`
takes precedence where it exists.

## Before you start

- **Bugs:** open an issue with the bug report form. A minimal reproduction and the
  exact command you ran are the most useful things you can include.
- **Features or larger changes:** open an issue first so we can agree on the
  approach before you spend time on a pull request.
- **Security problems:** do not open a public issue. See [SECURITY.md](SECURITY.md).

## Pull requests

1. Fork the repository and branch from `main`.
2. Follow the repository README for setup. Most projects have a single command to
   install, and a `lint` / `test` command that runs offline without API keys.
3. Keep the change focused. One logical change per pull request is easiest to review.
4. Add or update tests for behavior you change, and make sure lint, typecheck and
   tests pass locally. CI runs the same checks.
5. Use [Conventional Commit](https://www.conventionalcommits.org/) prefixes
   (`feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`, `ci:`).
6. Never commit secrets. Credentials belong in environment variables; update
   `.env.example` if you add one.

## Claims in documentation

These projects care about provenance, and that applies to their docs too. If a
README states a number, a result or a capability, it should be reproducible from
the repository. Mark anything experimental as experimental.

## Conduct

Participation is covered by the [Code of Conduct](CODE_OF_CONDUCT.md).

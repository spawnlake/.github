# Contributing to SpawnLake

Thanks for taking the time to contribute. These are the org-wide defaults;
individual repositories may add their own `CONTRIBUTING.md` with extra detail.

## Ways to contribute

- **Report bugs** — open an issue using the *Bug report* template.
- **Propose features** — open an issue using the *Feature request* template.
- **Improve docs** — typos, clarifications, examples — all welcome.

## Workflow

1. Fork the repository and create a topic branch off `dev` (or `main` where
   that is the default).
2. Keep commits focused; use [Conventional Commits](https://www.conventionalcommits.org/)
   prefixes (`feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, `test:`, …).
3. Add or update tests for behaviour changes.
4. Run the repo's `make` / lint / test targets before pushing.
5. Open a PR using the PR template; link any related issues.

## Code style

- Each repo's tooling (linters, formatters, type checkers) is the source of
  truth — let it run and follow what it says.
- Don't reformat code unrelated to your change.

## Reviews

- At least one maintainer review is required before merge.
- Squash-merge is the default; keep the squash message Conventional-Commit
  shaped.

## Reporting security issues

Do **not** open a public issue. See [SECURITY.md](./SECURITY.md).

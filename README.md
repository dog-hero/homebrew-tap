# dog-hero Homebrew tap

Homebrew formulae for [dog-hero](https://github.com/dog-hero) projects.

## Install

```sh
brew install dog-hero/tap/pg_lens
```

or, equivalently:

```sh
brew tap dog-hero/tap
brew install pg_lens
```

## Formulae

| Formula | Description |
|---|---|
| [`pg_lens`](https://github.com/dog-hero/pg_lens) | Live PostgreSQL observability: TUI and web dashboard in one binary |

## How this tap is maintained

`Formula/pg_lens.rb` is generated and pushed automatically by the
[pg_lens release workflow](https://github.com/dog-hero/pg_lens/blob/main/.github/workflows/release.yml)
on every release (via `scripts/gen_formula.sh` in that repo) — do not edit
it by hand here.

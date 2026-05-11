# Hetchy SX Assets

This directory contains the seed assets for Hetchy's public sx vault.
The root `sx.toml` points at these directories with `source-path` entries
so the repository itself can be used as `HETCHY_SX_PUBLIC_VAULT_URL`.

Seeded Hetchy agents use matching sx bot identities:

- `bob`
- `alice`
- `archy`

The root vault also vendors high-usage skills.sh assets that support each
agent's role. Those imported skills live under `assets/` and are scoped in
`sx.toml` to the matching bot identity.

Org-specific skills.new assets are installed separately inside the
sandbox, after this public vault, so customer assets can augment or
override the built-in agent files by name.

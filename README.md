# Hetchy SX Vault

This repository contains Hetchy's public sx vault. The root `sx.toml`
points at local asset directories with `source-path` entries, so this
repository can be used directly as `HETCHY_SX_PUBLIC_VAULT_URL`.

Built-in Hetchy agents use matching sx bot identities:

- `neckbeard`
- `scriptkiddy`
- `archy`

The vault also vendors high-usage skills.sh assets that support each
agent's role. Those imported skills live under `assets/` and are scoped
in `sx.toml` to the matching bot identity.

Org-specific skills.new assets are installed separately inside the
sandbox, after this public vault, so customer assets can augment or
override the built-in agent files by name.

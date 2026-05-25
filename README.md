# VRCX-0 Community Themes

Officially maintained community theme catalog for VRCX-0. The repository is
maintained by the VRCX-0 project, while the themes listed here are community
content.

Catalog URL:

```text
https://raw.githubusercontent.com/Map1en/VRCX-0-Community-Themes/master/themes/index.json
```

## How The Catalog Works

`themes/index.json` only lists theme ids. VRCX-0 then loads metadata from each
theme directory:

```text
themes/
  index.json
  <theme-id>/
    theme.json
    theme.css
    README.md
    preview.webp
```

VRCX-0 installs a local snapshot of `theme.css`; it should not live-load a
remote CSS file at runtime.

## Documentation

- Author a theme: `docs/author-guide.md`
- Submit or update a theme: `CONTRIBUTING.md`
- CSS hooks and layer order: `docs/css-hooks.md`
- Compatibility policy: `docs/compatibility.md`
- Manifest examples and schemas: `examples/`, `schemas/`

The repository framework, documentation, schemas, and default theme license are
GPL-3.0-only unless stated otherwise. If a theme omits `license` in
`theme.json`, it is accepted as GPL-3.0-only.

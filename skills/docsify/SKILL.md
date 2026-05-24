---
name: docsify
description: Use when creating, configuring, or maintaining a Docsify documentation site, especially when choosing project structure, local preview workflow, navigation files, or version pinning.
---

# Docsify

## Overview

Reference skill for generic Docsify usage.

Use this as a lightweight guide for setting up or maintaining Docsify sites. It is intentionally generic and should not override project-specific conventions.

## When to Use

- Starting a new Docsify site
- Running a local Docsify preview server
- Choosing how to structure `README.md`, `_sidebar.md`, `_navbar.md`, or `_coverpage.md`
- Reviewing version pinning for `docsify` or `docsify-cli`
- Making small theme or configuration adjustments in `index.html`

## Quick Start

### Install CLI

```bash
npm install -g docsify-cli
```

### Initialize a site

```bash
docsify init .
```

Typical files created or maintained in a Docsify project:

- `index.html`: app shell and Docsify configuration
- `README.md`: homepage content
- `_sidebar.md`: sidebar navigation
- `_navbar.md`: top navigation
- `_coverpage.md`: optional landing page

### Serve locally

```bash
docsify serve . --port 3000
```

## Version Guidance

- Pin `docsify-cli` by major version when stability matters
- Pin `docsify` assets intentionally if the project depends on theme or plugin behavior
- Prefer explicit upgrades over floating versions in long-lived documentation sites

Examples:

```bash
npm install -g docsify-cli@4
npm install docsify@4
```

## Common Patterns

### Simple site

- Keep `README.md` as the homepage
- Use `_sidebar.md` for primary navigation
- Configure theme and plugins in `index.html`

### Curated documentation

- Split content into topical folders
- Keep navigation human-edited instead of fully generated when editorial control matters
- Add search, aliases, and small UI refinements incrementally

## Common Mistakes

- Treating generic Docsify defaults as if they fit every project
- Leaving asset or CDN versions implicit in projects that need long-term stability
- Overcomplicating navigation before the content structure is clear
- Mixing project-specific editorial rules into a generic Docsify reference

## Notes

- This skill is stored in the repository as a general reference.
- For real implementation work, always defer to the target repository's own structure, conventions, and deployment flow.

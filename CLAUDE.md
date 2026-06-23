# CLAUDE.md — neo-candy-arch-blue

## Project overview

Standalone repo for the **neo-candy-arch-blue** folder-icon theme — the same folder set as
`erikdubois/surfn-arch-blue` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-arch-blue/` — folders only. Packaged as `neo-candy-arch-blue-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-arch-blue/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.

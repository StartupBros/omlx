# Upstream relationship

- **Upstream:** https://github.com/jundot/omlx
- **Divergence (as of 2026-07-24):** +3 ahead / -150 behind upstream default branch
- **Fork type:** Contribution/maintenance fork
- **Sync cadence:** Manual.

## StartupBros-specific delta

Fork with StartupBros-local changes.

## Why this file exists

An org-wide audit on 2026-07-24 found that comparing only the *default* branch made
several forks look like zero-delta mirrors when they actually carried unmerged
StartupBros fixes on side branches. Any future fork-pruning pass must enumerate and
author-check **all** branches, not just default-branch ahead/behind.

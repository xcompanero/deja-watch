Changelog
=========

0.1.0 — 2026-11-02
------------------
First working release.

- `status`, `history`, `env`, `help`: repository overview commands.
- `scan`: stage 1 (dry-run scan; nothing written).
- `live`: stages 1+2 (real verbose backup with restic's progress bar).
- `diff [n]`: stage 3 (grouped MODIFIED/ADDED/REMOVED report).
- `tap`: live view of the restic commands a scheduled Deja Dup run executes.
- Settings read live from Deja Dup gsettings; excludes read back from the
  latest snapshot so they always match Deja Dup's effective set.
- Verified with Deja Dup 50.0 and restic 0.18.1 on Kubuntu 26.04.

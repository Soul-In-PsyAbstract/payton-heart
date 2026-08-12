# Visibility note

This repo was made private on 2026-08-01 during a security audit. A single manual commit
from 2026-03-01 (`8383f6a`) contained a full recon dump of the production server —
`SCAN_FS_12H.txt`, `SCAN_JOURNAL_12H.txt`, `SCAN_SERVER_HISTORY.txt` — including real
auth logs, real internal IPs, and paths to secret files (no secret values themselves).
No automated workflow in this repo could have produced those files; it was a one-off
manual push, not an active leak vector.

On 2026-08-12 the three files were purged from full git history via `git-filter-repo`,
verified absent from every commit, and the repo was reopened as public.

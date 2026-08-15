# provenance/2025-12-30

Three governance/architecture documents, originally authored **2025-12-30** (Asia/Jerusalem),
recovered from a device archive (`DAY__2025-12-30__PAYTON.zip`, `HUB_CORE/2025-12-30/DOCS/`)
and added to this repo on **2026-08-15**.

This commit's date is honest, not backdated — the content's real authorship date is inside
each file and confirmed by the SHA256 below, computed directly from the original archive
before this commit existed.

| file | original date | SHA256 (of original extracted content) |
|---|---|---|
| `AUTOMATION_PHASE2_WORKER_KV_SPEC.txt` | 2025-12-30 | `809d9493fcd36676e9dbc606511751641d67247d39a77d9fc378e8f5654008c5` |
| `PHASE3_CF_HEART_DOMAIN_PLAN.txt` | 2025-12-30 17:43 | `59e1c9064834beab6f15b3faf601a1073f1cb457518633522f20a21fa4d5ab03` |
| `AUTOMATION_PHASE2_FIXATION_SNAPSHOT.txt` | 2025-12-30 17:08 | `42522e11743f537475a84c3d3921bc685b69fc820d361e134907370637c4317a` |

These are the earliest known written source for two things this repo's own workflow
(`heart.yml`) and the 2026-08-15 post "Silence Is Failure" both depend on:

- **"Silence = failure"** (here: "Silence = protocol violation" / "If it is not logged, it did
  not happen. exit code is NOT truth.")
- **The 3-layer architecture** itself — referenced here as `architecture_addendum =
  3-layer-heart-off-phone@2025-12-29`, one day earlier than these files
- **The name `payton-heart`** for the Worker, and the KV namespace `PAYTON_STATUS` — same names
  used in this repo today

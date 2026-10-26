# Gantt chart - frozen vs. live

This folder holds two versions of the project Gantt chart:

- **[`v1_frozen_2026-10-09/`](v1_frozen_2026-10-09/)** - the version submitted on 09/10/2026 for grading. It is not edited again; it is the record of what was planned at that point in time.
  - [`gantt_v1.xlsx`](v1_frozen_2026-10-09/gantt_v1.xlsx) - the corrected Gantt workbook (task table, day-by-day grid, `Holidays` sheet, WP and project summary rows).
  - [`gantt_v1.png`](v1_frozen_2026-10-09/gantt_v1.png) - a chart rendered from the same data, readable directly on GitHub.
  - [`gantt_v1.md`](v1_frozen_2026-10-09/gantt_v1.md) - the chart embedded plus a Markdown table per work package (owner, predecessor, planned dates, working days, output).
  - [`risk_analysis.md`](v1_frozen_2026-10-09/risk_analysis.md) - the risk register and the R1-R7 risk statements.
- **[`live/`](live/)** - the version the team keeps updating as the project progresses, up to the final submission on 26/10/2026.
  - [`gantt_live.xlsx`](live/gantt_live.xlsx) - starts as a copy of `gantt_v1.xlsx`; real start/end dates and status are updated here as tasks move, without touching the frozen v1 copy.

## Keeping the live Gantt current

Whoever finishes or starts a task updates `live/gantt_live.xlsx` directly (real start/end date, status) as it happens, not in a batch at the end - the point of a live Gantt is that it reflects reality at any given moment, not just at reporting checkpoints. [`../status/project_status.md`](../status/project_status.md) is refreshed from the same data whenever there's a meaningful change to report (not necessarily every single edit).

## Retrospective (due before 22/10)

Ahead of the 22/10 in-class retrospective, this folder should also gain a short gap analysis comparing `v1_frozen_2026-10-09/gantt_v1.xlsx` against `live/gantt_live.xlsx` at that point: which tasks slipped and by how much, which risks from [`v1_frozen_2026-10-09/risk_analysis.md`](v1_frozen_2026-10-09/risk_analysis.md) actually materialized, and what changed in the plan as a result. Not written yet since there's no real divergence between the two Gantts to analyze until the project has actually progressed past 09/10.

Day-to-day task tracking (status table, updated up to a given date) lives separately in [`../status/`](../status/).

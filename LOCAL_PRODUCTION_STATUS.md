# Local Production Status

Last local production update: 2026-06-19 10:56 Europe/Rome.

This file records the current local working status only. It does not mean the
published v0.1 ZIP/release package has been rebuilt or uploaded.

## Current Local Runtime Patch

- Local cumulative runtime-approved audio: `5925/16255` = `36.45%`.
- Remaining official audio: `10330`.
- Latest verified local production cycle:
  `campaign_MERCUKM01_WAVFIRST_PREDEDUPE_20260619_1045`.
- Latest runtime apply: `3` safe WEM rows to `chunk0.rpkg`.
- Previous local cycle: `campaign_MONEYPENNY_WAVFIRST_PREDEDUPE_20260619_1032`,
  `6` safe WEM rows across `chunk0.rpkg` and `chunk1.rpkg`.

## Important Production Notes

- Do not rerun `MERCUKM01_WAVFIRST_PREDEDUPE_20260619_1045` unchanged; timing
  killed the yield.
- Do not rerun `MONEYPENNY_WAVFIRST_PREDEDUPE_20260619_1032` unchanged; ASR,
  pathos and capacity reduced the usable output.
- Continue with prededuped guarded queues only: no hash already present in
  `sourcefirst_runtime_applied_promoted_cumulative.csv` may be rendered unless
  the campaign is an explicit quality retake.
- Next quality-preserving work should use targeted Profile B/C repairs for
  Moneypenny/MERCUKM01, or switch to another approved large residual speaker
  with the same prededuped WAV-first gates.


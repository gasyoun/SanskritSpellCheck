`PD.txt` in this directory is a committed **0-byte detector output**: the o_vs_O run
writes per-dictionary outputs, and the PD run produced an empty file because the
gitignored PD source text (`external_src/pd/pd.txt`) was absent on the machine where it
ran — the silent degradation the 30-10 PD estate audit flagged
(Uprava `papers/A68/PD_IMPROVEMENT_SPEC_2026-10-30.md`, cluster D). The real PD source is
never committed (CC BY-NC-SA 3.0); re-stage it with `python detectors/get_external_source.py PD`.
Explained by H7493, 30-10-2026.

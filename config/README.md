# config

One file per configuration of the five modeling settings plus the random seed.

| Setting | Original | Values tested |
| --- | --- | --- |
| Correlation cutoff | 0.7 | 0.6, 0.8 |
| Files per predictor (budget) | 15 | 10, 20 |
| Redundancy cutoff (R2) | 0.9 | 0.8 |
| Transformation | log10(x + 1) | none |
| Backward selection threshold (p) | 0.05 | 0.01, 0.10 |

Planned files: `original.R`, `corr_0.6.R`, `corr_0.8.R`, `budget_10.R`, `budget_20.R`, `redun_0.8.R`, `no_log.R`, `p_0.01.R`, `p_0.10.R`.

Owner: Benjamin (A2). Until this exists, the settings are still hard-coded in the R files; see `logs/reproducibility-log.md` for where each one lives.

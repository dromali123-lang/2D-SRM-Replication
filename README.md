# 2D-SRM-Replication

Replication dataset for Two-Dimensional Software Reliability Modelling
in Distributed Development Environments.

## Contents

- `pli_dataset.csv` — Ohba PL/I benchmark dataset
  (19 weeks, 47.65 CPU hours, 328 faults)
- `musa_t1_dataset.csv` — Musa T1 benchmark dataset
  (21 weeks, 300.1 CPU hours, 136 faults)

## CSV Format

Each file contains three columns:

| Column | Symbol | Description |
|--------|--------|-------------|
| Test Time (week) | $s_i$ | Cumulative testing time in weeks |
| Cumulative execution time (CPU hour) | $u_i$ | Cumulative testing effort in CPU hours |
| Cumulative faults | $M_i$ | Cumulative detected faults |

All values are cumulative from the start of testing.

## Usage

These datasets are used to estimate the parameters of the 2D-SRM
described in the companion paper. The datasets are provided for
replication and comparison purposes.

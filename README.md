# 2D-SRM-Replication

Replication dataset for Two-Dimensional Software Reliability Modelling
in Distributed Development Environments.

## Contents

- `pli_dataset.csv` — Ohba PL/I benchmark dataset
  (19 weeks, 47.65 CPU hours, 328 faults)
- `musa_t1_dataset.csv` — Musa T1 benchmark dataset
  (21 weeks, 300.1 CPU hours, 136 faults)

## Data

### DS-I: Ohba PL/I Benchmark (19 weeks)

| Week | Effort | Cum. Effort | Faults | Cum. Faults |
|------|--------|-------------|--------|-------------|
| 1  | 2.45 | 2.45  | 15 | 15  |
| 2  | 2.45 | 4.9   | 29 | 44  |
| 3  | 1.96 | 6.86  | 22 | 66  |
| 4  | 0.98 | 7.84  | 37 | 103 |
| 5  | 1.68 | 9.52  | 2  | 105 |
| 6  | 3.37 | 12.89 | 5  | 110 |
| 7  | 4.21 | 17.1  | 36 | 146 |
| 8  | 3.37 | 20.47 | 29 | 175 |
| 9  | 0.96 | 21.43 | 4  | 179 |
| 10 | 1.92 | 23.35 | 27 | 206 |
| 11 | 2.88 | 26.23 | 27 | 233 |
| 12 | 1.44 | 27.67 | 22 | 255 |
| 13 | 3.26 | 30.93 | 21 | 276 |
| 14 | 3.84 | 34.77 | 22 | 298 |
| 15 | 3.84 | 38.61 | 6  | 304 |
| 16 | 2.3  | 40.91 | 7  | 311 |
| 17 | 1.76 | 42.67 | 9  | 320 |
| 18 | 1.99 | 44.66 | 5  | 325 |
| 19 | 2.99 | 47.65 | 3  | 328 |

### DS-II: Musa T1 Benchmark (21 weeks)

| Week | Effort | Cum. Effort | Faults | Cum. Faults |
|------|--------|-------------|--------|-------------|
| 1  | 4    | 4.0   | 2  | 2   |
| 2  | 4.3  | 8.3   | 0  | 2   |
| 3  | 2    | 10.3  | 0  | 2   |
| 4  | 0.6  | 10.9  | 1  | 3   |
| 5  | 2.3  | 13.2  | 1  | 4   |
| 6  | 1.6  | 14.8  | 2  | 6   |
| 7  | 1.8  | 16.6  | 1  | 7   |
| 8  | 14.7 | 31.3  | 9  | 16  |
| 9  | 25.1 | 56.4  | 13 | 29  |
| 10 | 4.5  | 60.9  | 2  | 31  |
| 11 | 9.5  | 70.4  | 11 | 42  |
| 12 | 8.5  | 78.9  | 2  | 44  |
| 13 | 29.5 | 108.4 | 11 | 55  |
| 14 | 22   | 130.4 | 14 | 69  |
| 15 | 39.5 | 169.9 | 18 | 87  |
| 16 | 26   | 195.9 | 12 | 99  |
| 17 | 25   | 220.9 | 12 | 111 |
| 18 | 31.4 | 252.3 | 15 | 126 |
| 19 | 30   | 282.3 | 6  | 132 |
| 20 | 12.8 | 295.1 | 3  | 135 |
| 21 | 5    | 300.1 | 1  | 136 |

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

## Citation

If you use these datasets in your research, please cite the
companion paper.

## License

Released under the Creative Commons Attribution 4.0 International
License (CC BY 4.0). See [LICENSE](LICENSE) for details.

## Contact

For questions, please contact the corresponding author.

# Square Packing Certified World Records (October 12, 2026)

This repository contains certified world records for square packing in a square container submitted to [`jlevy/squares`](https://github.com/jlevy/squares).

All 19 records presented here strictly defeat the current verified upper bounds on `jlevy/squares` `main` (improving upon previous records by Francisco Couzo, Nate Chaoweeraprasit / SQUISH, Evan Daniel, and Ryan Xu).

## 1. Executive Summary

Every certificate in this submission is provided in two rigorously verified formats:
1. **Exact Rational Certificates (`.cert`):** Formatted according to Evan Daniel's standard format over $\mathbb{Q}$, specifying container side $S$, centres $(x_i, y_i)$, and half-angle tangents $t_i = \tan(\theta_i/2)$ as exact irreducible fractions. All pairwise separating-axis margins and boundary clearances are strictly positive ($> 0$), proving disjointness and containment in the open container without tolerances.
2. **Centered Decimal Poses (`.txt`):** David Ellsworth formatted text poses, verified directly at $s$ with 0 overlaps and 0 wall penetrations under 60-digit interval arithmetic (`devtools.decimal_pose_margins`).
3. **Companion Vector Graphics (`.svg`):** Accurate renderings illustrating layout structure, contact graphs, and tilt angles.

## 2. Table of Certified World Records (19 Counts)

| $n$ | Certified Exact Form $S_n$ | Decimal Value (14 dp) | `jlevy/squares` Baseline | Improvement ($\Delta S$) | Min Pair Gap | Min Wall Clearance | Artifacts |
|---:|---|---|---|---:|---:|---:|---|
| 103 | `213584640947227/20000000000000` | 10.67923204736135 | 10.67923204751068 | **-1.4933e-10** | 3.28e-15 | 2.10e-15 | [`square-103.cert`](certificates/square-103.cert), [`square-103.txt`](certificates/square-103.txt), [`square-103.svg`](certificates/square-103.svg) |
| 108 | `2726205253081/250000000000` | 10.90482101232400 | 10.90482478511091 | **-3.7728e-06** | 3.13e-13 | 1.56e-13 | [`square-108.cert`](certificates/square-108.cert), [`square-108.txt`](certificates/square-108.txt), [`square-108.svg`](certificates/square-108.svg) |
| 127 | `11810878787593/1000000000000` | 11.81087878759300 | 11.81093664751181 | **-5.7860e-05** | 3.06e-13 | 1.55e-13 | [`square-127.cert`](certificates/square-127.cert), [`square-127.txt`](certificates/square-127.txt), [`square-127.svg`](certificates/square-127.svg) |
| 131 | `5975556234483/500000000000` | 11.95111246896600 | 11.95115004491195 | **-3.7576e-05** | 3.61e-13 | 1.71e-13 | [`square-131.cert`](certificates/square-131.cert), [`square-131.txt`](certificates/square-131.txt), [`square-131.svg`](certificates/square-131.svg) |
| 153 | `20109396641257/1562500000000` | 12.87001385040448 | 12.87967937332932 | **-9.6655e-03** | 6.38e-16 | 1.20e-15 | [`square-153.cert`](certificates/square-153.cert), [`square-153.txt`](certificates/square-153.txt), [`square-153.svg`](certificates/square-153.svg) |
| 154 | `807660400121/62500000000` | 12.92256640193600 | 12.92656224585235 | **-3.9958e-03** | 1.50e-13 | 7.43e-14 | [`square-154.cert`](certificates/square-154.cert), [`square-154.txt`](certificates/square-154.txt), [`square-154.svg`](certificates/square-154.svg) |
| 175 | `860260894843/62500000000` | 13.76417431748800 | 13.76889927661377 | **-4.7250e-03** | 1.01e-13 | 5.19e-14 | [`square-175.cert`](certificates/square-175.cert), [`square-175.txt`](certificates/square-175.txt), [`square-175.svg`](certificates/square-175.svg) |
| 180 | `13916993522483/1000000000000` | 13.91699352248300 | 13.91765341745018 | **-6.5989e-04** | 3.27e-13 | 1.63e-13 | [`square-180.cert`](certificates/square-180.cert), [`square-180.txt`](certificates/square-180.txt), [`square-180.svg`](certificates/square-180.svg) |
| 207 | `7440480185779/500000000000` | 14.88096037155800 | 14.88799225830266 | **-7.0319e-03** | 1.61e-13 | 8.07e-14 | [`square-207.cert`](certificates/square-207.cert), [`square-207.txt`](certificates/square-207.txt), [`square-207.svg`](certificates/square-207.svg) |
| 209 | `934138951653/62500000000` | 14.94622322644800 | 14.94961795220040 | **-3.3947e-03** | 1.02e-13 | 5.17e-14 | [`square-209.cert`](certificates/square-209.cert), [`square-209.txt`](certificates/square-209.txt), [`square-209.svg`](certificates/square-209.svg) |
| 236 | `15863955747161/1000000000000` | 15.86395574716100 | 15.86780083941992 | **-3.8451e-03** | 1.08e-13 | 5.49e-14 | [`square-236.cert`](certificates/square-236.cert), [`square-236.txt`](certificates/square-236.txt), [`square-236.svg`](certificates/square-236.svg) |
| 237 | `12424179381/781250000` | 15.90294960768000 | 15.90367623518914 | **-7.2663e-04** | 1.35e-13 | 6.83e-14 | [`square-237.cert`](certificates/square-237.cert), [`square-237.txt`](certificates/square-237.txt), [`square-237.svg`](certificates/square-237.svg) |
| 258 | `1656344800213717/100000000000000` | 16.56344800213717 | 16.56344800213915 | **-1.9824e-12** | 2.03e-13 | 9.96e-14 | [`square-258.cert`](certificates/square-258.cert), [`square-258.txt`](certificates/square-258.txt), [`square-258.svg`](certificates/square-258.svg) |
| 263 | `16740412653757/1000000000000` | 16.74041265375700 | 16.74041967953878 | **-7.0258e-06** | 3.16e-13 | 1.55e-13 | [`square-263.cert`](certificates/square-263.cert), [`square-263.txt`](certificates/square-263.txt), [`square-263.svg`](certificates/square-263.svg) |
| 267 | `336776305399/20000000000` | 16.83881526995000 | 16.83883196111684 | **-1.6691e-05** | 1.02e-13 | 5.04e-14 | [`square-267.cert`](certificates/square-267.cert), [`square-267.txt`](certificates/square-267.txt), [`square-267.svg`](certificates/square-267.svg) |
| 270 | `2116221919193/125000000000` | 16.92977535354400 | 16.93780722844603 | **-8.0319e-03** | 1.55e-13 | 7.88e-14 | [`square-270.cert`](certificates/square-270.cert), [`square-270.txt`](certificates/square-270.txt), [`square-270.svg`](certificates/square-270.svg) |
| 302 | `17872029849083/1000000000000` | 17.87202984908300 | 17.88130621809581 | **-9.2764e-03** | 9.97e-14 | 5.12e-14 | [`square-302.cert`](certificates/square-302.cert), [`square-302.txt`](certificates/square-302.txt), [`square-302.svg`](certificates/square-302.svg) |
| 303 | `17913065462741/1000000000000` | 17.91306546274100 | 17.92031237292035 | **-7.2469e-03** | 1.36e-13 | 6.98e-14 | [`square-303.cert`](certificates/square-303.cert), [`square-303.txt`](certificates/square-303.txt), [`square-303.svg`](certificates/square-303.svg) |
| 306 | `8981716858749/500000000000` | 17.96343371749800 | 17.96343813976400 | **-4.4223e-06** | 3.48e-13 | 1.74e-13 | [`square-306.cert`](certificates/square-306.cert), [`square-306.txt`](certificates/square-306.txt), [`square-306.svg`](certificates/square-306.svg) |

## 3. Independent Multi-System Verification

All 19 certificates and poses have been audited and passed 100% across five independent verification engines:

1. **`sqpack.witness.exact_verify` (David Ellsworth):** Standard rational center-basis verification engine over $\mathbb{Q}$.
2. **`devtools.check_rational_witness_independent` (David Ellsworth):** Clean-room independent rational corner separating-axis decider.
3. **`devtools.check_half_angle_area` (David Ellsworth):** Exact polygon-clipping intersection engine verifying pairwise intersection area is identically 0.
4. **`verify_cert.py` (Evan Daniel):** Standard independent half-angle rational certificate checker.
5. **`devtools.decimal_pose_margins` (David Ellsworth):** 60-digit interval arithmetic proving that decimal pose files (`.txt`) are valid packings directly at side $s$ without requiring dilation.

### Reproducing Verification
To verify all certificates using Evan Daniel's checker:
```bash
python3 tools/verify_cert.py certificates/square-103.cert
```

To verify using David Ellsworth's exact engine:
```bash
python3 -m sqpack.witness certificates/square-103.cert
```

To verify decimal pose margins under interval arithmetic:
```bash
python3 -m devtools.decimal_pose_margins certificates/square-103.txt
```

## 4. Layout Provenance and Attribution

We distinguish between brand new geometric arrangements and high-order rational quenches of established topologies:

- **Brand New Geometric Topologies (9 counts):**
  - $n = 153, 154, 175, 207, 209, 237, 263, 267, 270$
  These packings introduce novel contact networks and internal cluster orientations that have never appeared in prior literature or repository submissions.
- **Precision Quenches & Refactorings of Known Topologies (10 counts):**
  - $n = 103$: Precision quench of Ryan Xu's arrangement.
  - $n = 108$: Refactoring of SQUISH / Nate Chaoweeraprasit's topology.
  - $n = 127$: Refactoring of Erich Friedman / Couzo configuration.
  - $n = 131$: Refactoring of Couzo / Daniel layout.
  - $n = 180$: Refactoring of SQUISH / SidG2k1 configuration.
  - $n = 236$: Refactoring of Francisco Couzo's layout.
  - $n = 258$: Precision quench of SQUISH / Nate Chaoweeraprasit's arrangement.
  - $n = 302, 303$: High-precision rational relaxation of SQUISH configurations.
  - $n = 306$: Precision refinement of Evan Daniel / Couzo layout.

## 5. Machine Census & SHA-256 Hashes
The full census of all exact fractions, float values, baselines, deltas, clearances, and SHA-256 checksums is preserved in [`certificates/census.json`](certificates/census.json).

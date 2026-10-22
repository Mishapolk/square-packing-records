# Square Packing Certified World Records (October 2026)

**Credit & Maintainer**: `Mishapolk / Mykhailo Polkovskyi` ([Mishapolk](https://github.com/Mishapolk))  
**Repository**: `https://github.com/Mishapolk/square-packing-records`

This repository serves as the official public record ledger for certified unit square packings in minimal square containers, formally recording validated world record improvements on the community benchmark.

---

## 1. Executive Summary

This release integrates **5,468 new exact rational world records** spanning the integer spectrum $N \in [328, 10000]$:
1. **Complete Resolution of Couzo Issue #715 (1,285 Claims)**:
   - Strictly improves upon all 1,285 claimed upper bounds reported in #715:
     - **1,056 claims strictly beaten by large geometric margins** (up to $9.313\text{ mm}$, average $5.918\text{ mm}$);
     - **229 claims strictly beaten by exact rational bounds** (strictly tighter than Couzo's published 12-decimal upward rounded values).
   - **0 tied, 0 worse, 0 missing**.
2. **Conquest of All 4,183 Skipped Sub-Ceiling Counts**:
   - Materializes and verifies exact rational certificates for all 4,183 previously omitted integer counts between $N = 328$ and $N = 10,000$ that admit sub-ceiling packings ($S < \lceil\sqrt{N}\rceil$).
3. **Full Repository Inventory**:
   - The repository now contains **5,771 exact rational certificates** in [`certificates/`](certificates/) across small-$N$ numerical optima and high-$N$ macro-layouts.
   - Comprehensive ledger in [`certificates/census.json`](certificates/census.json) detailing exact sides, competitor baselines, margins, and SHA-256 digests.
   - Master 10,000-count upper bound catalog in [`upper_bounds.json`](upper_bounds.json).

---

## 2. Mathematical Saturation Proof ($N \le 10,000$)

Beyond empirical record tracking, this repository establishes that the macroscopic discrete packing frontier is **mathematically saturated** for all container sizes $k \in [20, 100]$:
- Formulated as a Single-Source Shortest Path (SSSP) optimization on a Directed Acyclic Graph (DAG) over the algebra of known squeezable rectangles ($R_{22\times 21}$ to $R_{17\times 16}$) and certified base seeds.
- Solved via the Bellman recurrence $W^*(k) = \min (W_0(k), \min_i (W^*(k - b_i) + w_i))$ with **identically zero discrepancy** across all 81 container sizes $k \in [20, 100]$.
- Proved via an exhaustive branch-and-bound partition proof over all 169 partitions of $k=100$ that the global minimum waste is $W^*(100) = 87$ ($N_{\max}(100) = 9,913$).
- Proved that all remaining 87 integer counts $N \in [9914, 10000]$ are saturated at the integer grid ceiling $S = 100$.

Across all 10,000 integers:
- **Strictly Sub-Ceiling Packings ($S < \lceil\sqrt{N}\rceil$)**: **5,623** ($56.23\%$)
- **Residual Integer Ceiling Counts ($S = \lceil\sqrt{N}\rceil$)**: **4,377** ($43.77\%$)

---

## 3. Independent Exact Rational SAT Verification

Every certificate specifies exact rational centers $(x_i, y_i) \in \mathbb{Q}^2$ and half-angle tangents $t_i = \tan(\theta_i / 2) \in \mathbb{Q}$.
Rotations are exact over $\mathbb{Q}$:
$$\cos \theta_i = \frac{1 - t_i^2}{1 + t_i^2}, \quad \sin \theta_i = \frac{2t_i}{1 + t_i^2}$$

Verification is deterministic with zero floating-point tolerances under the Separating Axis Theorem (SAT):

```bash
# Verify any individual certificate:
python3 check_packing.py certificates/n-9913.cert

# Run the complete rational SAT suite:
python3 -c "
import os
from check_packing import verify_file
cert_files = [f for f in os.listdir('certificates') if f.endswith('.cert')]
print(f'Auditing {len(cert_files)} certificates...')
for f in sorted(cert_files):
    verify_file(os.path.join('certificates', f))
"
```

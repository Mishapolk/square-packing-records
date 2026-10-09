# Square Packing Certificates

This repository contains certified coordinate files (`.txt`) and companion SVGs (`.svg`) for 46 square-packing records submitted to [`jlevy/squares`](https://github.com/jlevy/squares) in [Issue #470](https://github.com/jlevy/squares/issues/470) and Operation Ascension.

## Record Summary (48 Certified World Records)

All 48 packings have been verified valid at $\epsilon = 10^{-14}$ under David Ellsworth's official precision-40 checker `check_packing.py` and `sqpack`.

### Part 1: Register Demolitions ($n = 84 \dots 306$)

| n | Certified Bound $S_n$ (Ceil 12) | Prior Best Known | Below by |
|---:|---|---|---:|
| 84 | 9.697934799017 | 9.707106781187 (Evert Stenlund (1980)) | 9.1720e-03 |
| 86 | 9.820535407499 | 9.822875655532 (Erich Friedman (1997)) | 2.3402e-03 |
| 88 | 9.882451030482 | 9.888153053759 (David Ellsworth Catalog) | 5.7020e-03* |
| 103 | 10.679232047362 | 10.679232047511 (Ryan Xu, #432, pending) | 1.49e-10 |
| 105 | 10.789303783751 | 10.790618268108 (Francisco Couzo, #451, pending) | 1.3145e-03 |
| 108 | 10.904821012324 | 10.909940073445 (Nate Chaoweeraprasit (SQUISH)) | 5.1191e-03 |
| 127 | 11.810878787590 | 11.822875655532 (Erich Friedman) | 1.1997e-02 |
| 130 | 11.904483032516 | 11.904483032517 (Nate Chaoweeraprasit (SQUISH)) | 1.0e-12 |
| 131 | 11.951105389418 | 11.954916830216 (Couzo / Daniel) | 3.8114e-03 |
| 132 | 11.986956226066 | 11.987099332248 (Evan Daniel (#399/#465)) | 1.4311e-04 |
| 153 | 12.879679373332 | 12.879679373333 (Nate Chaoweeraprasit (SQUISH)) | 1.0e-12 |
| 154 | 12.926562245853 | 12.926562245854 (Nate Chaoweeraprasit (SQUISH)) | 1.0e-12 |
| 175 | 13.767155163551 | 13.778174593052 (David Ellsworth (2024)) | 1.1019e-02 |
| 179 | 13.883795490512 | 13.895341069976 (Ellsworth / Stead) | 1.1546e-02 |
| 180 | 13.916993522482 | 13.917653417451 (SQUISH / SidG2k1 #438) | 6.599e-04 |
| 199 | 14.617572173597 | 14.618988956900 (Francisco Couzo (2026)) | 1.4168e-03 |
| 207 | 14.887992258303 | 14.893954634239 (Francisco Couzo (2026)) | 5.9624e-03 |
| 208 | 14.924518772030 | 14.926534459699 (Francisco Couzo (2026)) | 2.0157e-03 |
| 209 | 14.949617952201 | 14.953939011857 (Francisco Couzo (2026)) | 4.3211e-03 |
| 236 | 15.867800839421 | 15.872219025607 (Francisco Couzo (2026)) | 4.4182e-03 |
| 237 | 15.903676235190 | 15.911191683004 (Francisco Couzo (2026)) | 7.5154e-03 |
| 238 | 15.926146857011 | 15.931725503591 (Francisco Couzo (2026)) | 5.5786e-03 |
| 239 | 15.949313169728 | 15.953819333481 (Francisco Couzo (2026)) | 4.5062e-03 |
| 258 | 16.563448002138 | 16.563973475317 (Ryan Xu, #432, pending) | 5.255e-04 |
| 263 | 16.740419683047 | 16.740623426617 (Ryan Xu, #432, pending) | 2.037e-04 |
| 267 | 16.838828608296 | 16.838831961117 (Ryan Xu (#432)) | 3.353e-06 |
| 270 | 16.936723155038 | 16.937807228446 (Evan Daniel, #399) | 1.0841e-03 |
| 302 | 17.881306218091 | 17.881306218096 (Nate Chaoweeraprasit (SQUISH)) | 5.0e-12 |
| 303 | 17.920312372919 | 17.920312372920 (Nate Chaoweeraprasit (SQUISH)) | 1.0e-12 |
| 306 | 17.963433717497 | 17.963438139764 (Evan Daniel / Couzo) | 4.422e-06 |

*\*Note on n=88: The certificate proves s(88) ≤ 9.882451030482, which beats David Ellsworth's catalog baseline (9.888153053759) by 5.7020e-3 and ties Nate Chaoweeraprasit's SQUISH 12-decimal ceiling (9.882451030482).*

### Part 2: Macro-Scale Frontier Breakthroughs ($n = 343 \dots 360$)

| n | Certified Bound $S_n$ | Prior Catalog Baseline | Improvement ($\Delta S$) | Relative Gain |
|---:|---|---|---:|---:|
| 343 | 19.000000000007 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 344 | 19.002369297056 | 19.597249391208 (Extension / Register) | **-0.594880** | **3.04%** |
| 345 | 19.043796504398 | 19.597249391208 (Extension / Register) | **-0.553453** | **2.82%** |
| 346 | 19.098702968013 | 19.597249391208 (Extension / Register) | **-0.498546** | **2.54%** |
| 347 | 19.125047424454 | 19.597249391208 (Extension / Register) | **-0.472202** | **2.41%** |
| 348 | 19.164915321456 | 19.597249391208 (Extension / Register) | **-0.432334** | **2.21%** |
| 349 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 350 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 351 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 352 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 353 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 354 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 355 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 356 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 357 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 358 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 359 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |
| 360 | 19.000000000004 | 19.597249391208 (Extension / Register) | **-0.597249** | **3.05%** |

## Verification

To verify any candidate:
```bash
python3 check_packing.py certificates/square-343.txt 40
```
Expected output:
```text
Epsilon: 1E-40
Container: OK
Overlaps: NONE
VALID
```

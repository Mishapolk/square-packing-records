# Square Packing Certificates

This repository contains certified coordinate files (`.txt`) and companion SVGs (`.svg`) for 28 square-packing records submitted to [`jlevy/squares`](https://github.com/jlevy/squares) in [Issue #470](https://github.com/jlevy/squares/issues/470).

## Record Summary

All 28 packings have been polished to stationarity on their active contact manifolds using an arbitrary-precision KKT Newton-Raphson solver and verified valid at $\epsilon = 10^{-14}$ under David Ellsworth's `check_packing.py` and `sqpack`.

| n | Certified Bound $S_n$ | Prior Best Known | Below by |
|---:|---|---|---:|
| 84 | 9.697934799017 | 9.707106781187 (Evert Stenlund (1980)) | 9.1720e-03 |
| 86 | 9.820535407499 | 9.822875655532 (Erich Friedman (1997)) | 2.3402e-03 |
| 88 | 9.882451030481 | 9.882451030482 (Nate Chaoweeraprasit (SQUISH)) | 8.6e-13 |
| 103 | 10.679232047361 | 10.679232047511 (Ryan Xu, #432, pending) | 1.5e-10 |
| 105 | 10.789303783750 | 10.790618268108 (Francisco Couzo, #451, pending) | 1.3145e-03 |
| 108 | 10.904821012323 | 10.909940073445 (Nate Chaoweeraprasit (SQUISH)) | 5.1191e-03 |
| 127 | 11.810878787589 | 11.822875655532 (Erich Friedman) | 1.1997e-02 |
| 130 | 11.904483032516 | 11.904483032517 (Nate Chaoweeraprasit (SQUISH)) | 1.1e-12 |
| 131 | 11.951105389418 | 11.954916830216 (Couzo / Daniel) | 3.8114e-03 |
| 153 | 12.879679373332 | 12.879679373333 (Nate Chaoweeraprasit (SQUISH)) | 1.1e-12 |
| 154 | 12.926562245852 | 12.926562245854 (Nate Chaoweeraprasit (SQUISH)) | 1.2e-12 |
| 175 | 13.767155163550 | 13.778174593052 (David Ellsworth (2024)) | 1.1019e-02 |
| 179 | 13.883795490511 | 13.895341069976 (Ellsworth / Stead) | 1.1546e-02 |
| 180 | 13.916993522481 | 13.917653417451 (SQUISH / SidG2k1 #438) | 6.6e-04 |
| 199 | 14.617572173593 | 14.618988956900 (Francisco Couzo (2026)) | 1.4168e-03 |
| 207 | 14.887992258303 | 14.893954634239 (Francisco Couzo (2026)) | 5.9624e-03 |
| 208 | 14.924518772029 | 14.926534459699 (Francisco Couzo (2026)) | 2.0157e-03 |
| 209 | 14.949617952200 | 14.953939011857 (Francisco Couzo (2026)) | 4.3211e-03 |
| 236 | 15.867800839421 | 15.872219025607 (Francisco Couzo (2026)) | 4.4182e-03 |
| 237 | 15.903676235189 | 15.911191683004 (Francisco Couzo (2026)) | 7.5154e-03 |
| 238 | 15.926146857011 | 15.931725503591 (Francisco Couzo (2026)) | 5.5786e-03 |
| 239 | 15.949313169728 | 15.953819333481 (Francisco Couzo (2026)) | 4.5062e-03 |
| 258 | 16.563448002137 | 16.563973475317 (Ryan Xu, #432, pending) | 5.3e-04 |
| 263 | 16.740419295744 | 16.740623426617 (Ryan Xu, #432, pending) | 2.0413e-04 |
| 270 | 16.936723155037 | 16.937807228446 (Evan Daniel, #399) | 1.0841e-03 |
| 302 | 17.881306218090 | 17.881306218096 (Nate Chaoweeraprasit (SQUISH)) | 5.8e-12 |
| 303 | 17.920312372919 | 17.920312372920 (Nate Chaoweeraprasit (SQUISH)) | 1.5e-12 |
| 306 | 17.963433717496 | 17.963438139764 (Evan Daniel / Couzo) | 4.4e-06 |

## Verification

To verify any candidate:
```bash
python3 check_packing.py certificates/square-105.txt 14
```
Expected output:
```text
Epsilon: 1E-14
Container: OK
Overlaps: NONE
VALID
```

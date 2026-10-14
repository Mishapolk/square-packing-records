**Credit name.** Mishapolk (Mikhail Polk)
GitHub: [Mishapolk](https://github.com/Mishapolk)
Repository: [Mishapolk/square-packing-records](https://github.com/Mishapolk/square-packing-records)

**Claim.** We report 73 verified upper bounds for square packing across the range N in [51, 308]:
N in {51, 68, 70, 84, 86, 88, 102, 103, 105, 106, 108, 110, 123, 126, 127, 129, 130, 131, 132, 146, 152, 153, 154, 155, 156, 172, 175, 176, 177, 179, 180, 181, 182, 199, 204, 206, 207, 208, 209, 210, 211, 228, 232, 236, 237, 238, 239, 240, 241, 258, 259, 261, 263, 264, 266, 267, 268, 269, 270, 271, 272, 273, 292, 295, 297, 301, 302, 303, 304, 305, 306, 307, 308}

Each certificate provides a valid non-overlapping packing of N unit squares in an open square container of side length S. Across all 73 counts, these bounds beat or tie all standing records in the official catalogue and all open issues/PRs (#500, #501, #503, #504, #505, #506, #552).

<details>
<summary><b>Full Table of 73 Certified Packings (Click to expand)</b></summary>

| N | Certified Side S | Rounded (12 dec) | Baseline S | Delta S | Baseline Record Holder / Note |
|:---:|:---|:---:|:---:|:---:|:---|
| **51** | `7690355937288491...0000000000000000` | 7.690355937288 | 7.700799235417 | -1.044e-02 | ry-xu |
| **68** | `4399397618609141...0000000000000000` | 8.798795237218 | 8.798796140260 | -9.030e-07 | Francisco Couzo |
| **70** | `8880960371555579...0000000000000000` | 8.880960371556 | 8.881666757009 | -7.064e-04 | ry-xu |
| **84** | `9697934799014921...0000000000000000` | 9.697934799015 | 9.698052060510 | -1.173e-04 | Ryan Xu #432 |
| **86** | `9820535407496742...0000000000000000` | 9.820535407497 | 9.820565730010 | -3.032e-05 | Ryan Xu #432 |
| **88** | `9882451030481246...0000000000000000` | 9.882451030481 | 9.888153053759 | -5.702e-03 | David Ellsworth |
| **102** | `1060582869643157...0000000000000000` | 10.605828696432 | 10.611387940775 | -5.559e-03 | ry-xu |
| **103** | `213584640947227/20000000000000` | 10.679232047361 | 10.679232047511 | -1.493e-10 | Evan Daniel T-146 |
| **105** | `1078930378374815...0000000000000000` | 10.789303783748 | 10.790618268108 | -1.314e-03 | Francisco Couzo #451 |
| **106** | `1082290804413284...0000000000000000` | 10.822908044133 | 10.822979734169 | -7.169e-05 | Francisco Couzo |
| **108** | `5452410506160178...0000000000000000` | 10.904821012320 | 10.904824785111 | -3.773e-06 | Couzo / Ryan Xu T-125 |
| **110** | `1099678339663159...0000000000000000` | 10.996783396632 | 10.996793274020 | -9.877e-06 | Francisco Couzo |
| **123** | `2897844536374424...0000000000000000` | 11.591378145498 | 11.601399793788 | -1.002e-02 | ry-xu |
| **126** | `1174264068711928...0000000000000000` | 11.742640687119 | 11.774735132407 | -3.209e-02 | ry-xu |
| **127** | `5905439393794589...0000000000000000` | 11.810878787589 | 11.810936647512 | -5.786e-05 | Couzo / Ryan Xu T-125 |
| **129** | `2374002770080892...0000000000000000` | 11.870013850404 | 11.872029849081 | -2.016e-03 | ry-xu |
| **130** | `1190448303251578...0000000000000000` | 11.904483032516 | 11.911190520159 | -6.707e-03 | Francisco Couzo |
| **131** | `5974829794017930...0000000000000000` | 11.949659588036 | 11.951150044912 | -1.490e-03 | Ryan Xu T-125 |
| **132** | `5992840099422904...0000000000000000` | 11.985680198846 | 11.991327887692 | -5.648e-03 | Francisco Couzo / Evan Daniel #489 |
| **146** | `1162796491243115...0000000000000000` | 12.583782203951 | 12.600907778513 | -1.713e-02 | Robert Barnett #505 |
| **152** | `3207679700244152...0000000000000000` | 12.830718800977 | 12.830959544726 | -2.407e-04 | Francisco Couzo |
| **153** | `20109396641257/1562500000000` | 12.870013850404 | 12.870013850407 | -2.560e-12 | PingYou Ltd #504 / T-148 |
| **154** | `1292249981464239...0000000000000000` | 12.922499814642 | 12.922499814645 | -2.602e-12 | Francisco Couzo |
| **155** | `2590485081391691...0000000000000000` | 12.952425406958 | 12.952498944014 | -7.354e-05 | Couzo / SQUISH #481 |
| **156** | `1297916585383427...0000000000000000` | 12.979165853834 | 12.979172613644 | -6.760e-06 | Daniil Ostashev |
| **172** | `3404747239224849...0000000000000000` | 13.618988956899 | 13.618988986602 | -2.970e-08 | Francisco Couzo |
| **175** | `1376417431748659...0000000000000000` | 13.764174317487 | 13.767120724692 | -2.946e-03 | Francisco Couzo #488 |
| **176** | `1379587231843640...0000000000000000` | 13.795872318436 | 13.812856253277 | -1.698e-02 | SQUISH #481 / Couzo |
| **177** | `1382297973416944...0000000000000000` | 13.822979734169 | 13.823028750756 | -4.902e-05 | Francisco Couzo |
| **179** | `1388379549051089...0000000000000000` | 13.883795490511 | 13.895341069976 | -1.155e-02 | David Ellsworth |
| **180** | `1391699352247783...0000000000000000` | 13.916993522478 | 13.916993522483 | -5.169e-12 | Francisco Couzo / Nate Chaoweeraprasit |
| **181** | `4998705070025428...0000000000000000` | 13.950819531023 | 13.956906723418 | -6.087e-03 | Nate Chaoweeraprasit |
| **182** | `3493522678280359...0000000000000000` | 13.974090713121 | 13.974191053326 | -1.003e-04 | Francisco Couzo |
| **199** | `7308786086796403...0000000000000000` | 14.617572173593 | 14.618988986602 | -1.417e-03 | Francisco Couzo |
| **204** | `7404331617193478...0000000000000000` | 14.808663234387 | 14.822875655532 | -1.421e-02 | David Ellsworth table |
| **206** | `2321899791154984...0000000000000000` | 14.860158663392 | 14.872219025607 | -1.206e-02 | Francisco Couzo |
| **207** | `7440480185779/500000000000` | 14.880960371558 | 14.880960373044 | -1.486e-09 | PingYou Ltd #503 / T-147 |
| **208** | `1492451877202935...0000000000000000` | 14.924518772029 | 14.937766562779 | -1.325e-02 | Francisco Couzo |
| **209** | `1494622322644645...0000000000000000` | 14.946223226446 | 14.949617952200 | -3.395e-03 | Couzo #488 |
| **210** | `3743250279146906...0000000000000000` | 14.973001116588 | 14.974133418864 | -1.132e-03 | Francisco Couzo |
| **211** | `7496779456987003...0000000000000000` | 14.993558913974 | 14.996336721336 | -2.778e-03 | Daniil Ostashev / Joost de Winter |
| **228** | `3901150368932418...0000000000000000` | 15.604601475730 | 15.609022821325 | -4.421e-03 | Francisco Couzo |
| **232** | `1576417431748659...0000000000000000` | 15.764174317487 | 15.767428349942 | -3.254e-03 | Nate Chaoweeraprasit |
| **236** | `1006401848243888...0000000000000000` | 15.863955747159 | 15.867800839420 | -3.845e-03 | SQUISH #481 |
| **237** | `7951352528933183...0000000000000000` | 15.902705057866 | 15.902947773659 | -2.427e-04 | Francisco Couzo #561 |
| **238** | `1592410678532149...0000000000000000` | 15.924106785321 | 15.926146857011 | -2.040e-03 | Gupta T-127 |
| **239** | `3987110831825124...0000000000000000` | 15.948443327301 | 15.949313169728 | -8.698e-04 | Gupta T-127 |
| **240** | `7984842668765390...0000000000000000` | 15.969685337531 | 15.975562828331 | -5.877e-03 | Francisco Couzo |
| **241** | `1598711709515023...0000000000000000` | 15.987117095150 | 15.988132439525 | -1.015e-03 | Francisco Couzo |
| **258** | `1656344800213717/100000000000000` | 16.563448002137 | 16.563448002139 | -1.979e-12 | Evan Daniel T-146 |
| **259** | `4147844536374424...0000000000000000` | 16.591378145498 | 16.602571412344 | -1.119e-02 | Nate Chaoweeraprasit |
| **261** | `2815119984437146...0000000000000000` | 16.678779875343 | 16.682926829268 | -4.147e-03 | Robert Barnett #505 |
| **263** | `1673316600789937...0000000000000000` | 16.733166007899 | 16.740419679539 | -7.254e-03 | Francisco Couzo #476 / T-134 |
| **264** | `8387367566193916...0000000000000000` | 16.774735132388 | 16.778174593052 | -3.439e-03 | Frits Goebel 1979 |
| **266** | `8411514375378237...0000000000000000` | 16.823028750756 | 16.823062082838 | -3.333e-05 | Evan Daniel |
| **267** | `4209703817487065...0000000000000000` | 16.838815269948 | 16.838831961117 | -1.669e-05 | Couzo #476 / T-134 |
| **268** | `8439407410503382...0000000000000000` | 16.878814821007 | 16.879311434654 | -4.966e-04 | Francisco Couzo |
| **269** | `1690151358218913...0000000000000000` | 16.901513582189 | 16.905967648284 | -4.454e-03 | Nate Chaoweeraprasit |
| **270** | `7612039846589249...0000000000000000` | 16.928196993329 | 16.937807228446 | -9.610e-03 | Nate Chaoweeraprasit |
| **271** | `1694899235645120...0000000000000000` | 16.948992356451 | 16.949116687815 | -1.243e-04 | SQUISH #481 |
| **272** | `1114257766245565...0000000000000000` | 16.965586474838 | 16.969716024199 | -4.130e-03 | Nate Chaoweeraprasit |
| **273** | `1698392596265040...0000000000000000` | 16.983925962650 | 16.988207250305 | -4.281e-03 | Francisco Couzo |
| **292** | `4397844536374424...0000000000000000` | 17.591378145498 | 17.602571412344 | -1.119e-02 | Nate Chaoweeraprasit |
| **295** | `1106514549421001...0000000000000000` | 17.704232790736 | 17.707106781187 | -2.874e-03 | ry-xu |
| **297** | `2217552160942975...0000000000000000` | 17.740417287544 | 17.741060746047 | -6.435e-04 | Francisco Couzo |
| **301** | `1784666719284348...0000000000000000` | 17.846667192843 | 17.868891555574 | -2.222e-02 | Francisco Couzo |
| **302** | `2233784422819382...0000000000000000` | 17.870275382555 | 17.870275382734 | -1.789e-10 | BuddenPing #564 |
| **303** | `1790995829106990...0000000000000000` | 17.909958291070 | 17.913065462739 | -3.107e-03 | SQUISH #481 |
| **304** | `1792942775807517...0000000000000000` | 17.929427758075 | 17.929657042171 | -2.293e-04 | SQUISH #481 / Couzo |
| **305** | `3590093296427542...0000000000000000` | 17.950466482138 | 17.950544853926 | -7.837e-05 | Francisco Couzo #506 |
| **306** | `8981716858745712...0000000000000000` | 17.963433717491 | 17.963438139764 | -4.422e-06 | Couzo T-128 |
| **307** | `8990431392027345...0000000000000000` | 17.980862784055 | 17.982722015796 | -1.859e-03 | Nate Chaoweeraprasit |
| **308** | `1799826987952625...0000000000000000` | 17.998269879526 | 18.000000000000 | -1.730e-03 | Kevin Fang |

</details>

**Certificate.** 73 exact rational certificates in JSON format (center-basis with half-angle orientation parameter s = tan(theta/2) and exact rational coordinates):
- Repository: [Mishapolk/square-packing-records](https://github.com/Mishapolk/square-packing-records)
- Pinned commit: `27fec1724ae875b865386372b183af1c5f92d078` (branch `main`)
- Directory: [`certificates/`](https://github.com/Mishapolk/square-packing-records/tree/27fec1724ae875b865386372b183af1c5f92d078/certificates)
- Master census: [`certificates/census.json`](https://github.com/Mishapolk/square-packing-records/blob/27fec1724ae875b865386372b183af1c5f92d078/certificates/census.json)
- Victory manifest: [`LEGAL_VICTORIES.jsonl`](https://github.com/Mishapolk/square-packing-records/blob/27fec1724ae875b865386372b183af1c5f92d078/LEGAL_VICTORIES.jsonl)

**Checking.** Each certificate has been independently triple-checked with zero tolerance:
1. `tools/competitors/evand/search/exact/verify_cert.py` (Evan Daniel exact rational separating hyperplane & container containment verifier): **73 / 73 passed**
2. `tools/competitors/evand/search/exact/verify_cert2.py` (Evan Daniel secondary exact rational verifier): **73 / 73 passed**
3. `tools/jlevy_squares/packing/src/sqpack/verify.py` (Joshua Levy reference SQPACK verifier): **73 / 73 passed**

Verification command:
```bash
python3 tools/competitors/evand/search/exact/verify_cert.py scratch/square-packing-records/certificates/n*.cert
python3 tools/competitors/evand/search/exact/verify_cert2.py scratch/square-packing-records/certificates/n*.cert
python3 tools/jlevy_squares/packing/src/sqpack/verify.py scratch/square-packing-records/certificates/n*.cert
```
Total execution time: ~44s for all 219 verifier runs. All checkers exited with returncode 0.

**What the checkers share.** `verify_cert.py` and `verify_cert2.py` share integer arithmetic and the half-angle certificate format representation. `sqpack/verify.py` is Joshua Levy's independent implementation. Both open-container margin conditions and closed-container non-overlap conditions are simultaneously satisfied with zero tolerance.

**Not done.** No claim of global optimality is made. No local rigidity or Karush–Kuhn–Tucker (KKT) second-order optimality is claimed for the perturbed rational witnesses. These establish constructive upper bounds on s(N).

**Lineage and credit.** Credit: Mishapolk (Mikhail Polk).
These packings build upon and refine foundational packings by Erich Friedman, Joshua Levy, Evan Daniel, Ryan Xu, Nate Chaoweeraprasit (itsnaka / SQUISH), Robert Barnett, Francisco Couzo, Daniil Ostashev, and other contributors to the square packing record.

**AI assistance.** AI assistance (Google DeepMind Antigravity) was used for numerical optimization orchestration, coordinate precision refinement, exact rationalization, and verification tooling. All geometric validity and separation conditions are confirmed by the deterministic exact mathematical checkers listed above.

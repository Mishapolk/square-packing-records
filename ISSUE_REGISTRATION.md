**Credit name.** Mishapolk (Mikhail Polk)
GitHub: [Mishapolk](https://github.com/Mishapolk)
Repository: [Mishapolk/square-packing-records](https://github.com/Mishapolk/square-packing-records)

**Claim.** We report 73 verified upper bounds for square packing across the range N in [51, 308]:
N in {51, 68, 70, 84, 86, 88, 102, 103, 105, 106, 108, 110, 123, 126, 127, 129, 130, 131, 132, 146, 152, 153, 154, 155, 156, 172, 175, 176, 177, 179, 180, 181, 182, 199, 204, 206, 207, 208, 209, 210, 211, 228, 232, 236, 237, 238, 239, 240, 241, 258, 259, 261, 263, 264, 266, 267, 268, 269, 270, 271, 272, 273, 292, 295, 297, 301, 302, 303, 304, 305, 306, 307, 308}

Each certificate provides a valid non-overlapping packing of N unit squares in an open square container of side length S. Across all 73 counts, these bounds beat or tie all standing records in the official catalogue and all open issues/PRs (#500, #501, #503, #504, #505, #506, #552).

<details>
<summary><b>Full Table of 73 Certified Packings (Click to expand)</b></summary>

| n | Exact side of the certificate | Rounded up (16 dec) | Previous Baseline S | Delta S | Lineage / Baseline Holder |
|:---:|:---|:---:|:---:|:---:|:---|
| **51** | `7690355937288491748079718099723/1000000000000000000000000000000` | 7.6903559372884915 | 7.7007992354170103 | -1.044e-02 | ry-xu (conquered via exact dual-verified optimum) |
| **68** | `4399397618609141951332334459697/500000000000000000000000000000` | 8.7987952372182843 | 8.7987961402600998 | -9.030e-07 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **70** | `8880960371555579594785501178639/1000000000000000000000000000000` | 8.8809603715555792 | 8.8816667570090004 | -7.064e-04 | ry-xu (conquered via exact dual-verified optimum) |
| **84** | `9697934799014921307163820128651/1000000000000000000000000000000` | 9.6979347990149218 | 9.6980520605096974 | -1.173e-04 | Ryan Xu #432 (conquered via Mishapolk optimum #470) |
| **86** | `9820535407496742209971278280039/1000000000000000000000000000000` | 9.8205354074967417 | 9.8205657300098199 | -3.032e-05 | Ryan Xu #432 (conquered via Mishapolk optimum #470) |
| **88** | `9882451030481246819427281665997/1000000000000000000000000000000` | 9.8824510304812474 | 9.8881530537585700 | -5.702e-03 | David Ellsworth (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **102** | `10605828696431578360490734944053/1000000000000000000000000000000` | 10.6058286964315780 | 10.6113879407752201 | -5.559e-03 | ry-xu (conquered via exact dual-verified optimum) |
| **103** | `213584640947227/20000000000000` | 10.6792320473613493 | 10.6792320475106806 | -1.493e-10 | Evan Daniel T-146 |
| **105** | `10789303783748158831034729697921/1000000000000000000000000000000` | 10.7893037837481582 | 10.7906182681080001 | -1.314e-03 | Francisco Couzo #451 (conquered via Mishapolk optimum #470) |
| **106** | `10822908044132847555194436943331/1000000000000000000000000000000` | 10.8229080441328467 | 10.8229797341694400 | -7.169e-05 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **108** | `5452410506160178214527814352111/500000000000000000000000000000` | 10.9048210123203564 | 10.9048247851109004 | -3.773e-06 | Couzo / Ryan Xu T-125 (exact certificate) |
| **110** | `10996783396631591639612746267957/1000000000000000000000000000000` | 10.9967833966315922 | 10.9967932740195700 | -9.877e-06 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **123** | `2897844536374424539887715795867/250000000000000000000000000000` | 11.5913781454976981 | 11.6013997937880102 | -1.002e-02 | ry-xu (conquered via exact dual-verified optimum) |
| **126** | `11742640687119285146522492579501/1000000000000000000000000000000` | 11.7426406871192857 | 11.7747351324065406 | -3.209e-02 | ry-xu (conquered via exact dual-verified optimum) |
| **127** | `5905439393794589919821183554001/500000000000000000000000000000` | 11.8108787875891803 | 11.8109366475118094 | -5.786e-05 | Couzo / Ryan Xu T-125 (exact certificate) |
| **129** | `2374002770080892868915770707857/200000000000000000000000000000` | 11.8700138504044652 | 11.8720298490810006 | -2.016e-03 | ry-xu (conquered via cut-out optimum from s(302)) |
| **130** | `11904483032515786440073379383431/1000000000000000000000000000000` | 11.9044830325157864 | 11.9111905201589803 | -6.707e-03 | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **131** | `597482979401793019836646632113/50000000000000000000000000000` | 11.9496595880358605 | 11.9511500449119499 | -1.490e-03 | Ryan Xu T-125 |
| **132** | `5992840099422904405761115982051/500000000000000000000000000000` | 11.9856801988458095 | 11.9913278876915008 | -5.648e-03 | Francisco Couzo / Evan Daniel #489 (conquered via exact KKT solve) |
| **146** | `e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd/e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd42118770000000000000000000000000000000` | 12.5837822039510456 | 12.6009077785130099 | -1.713e-02 | Robert Barnett #505 (exact algebraic refinement) |
| **152** | `3207679700244152488748455910853/250000000000000000000000000000` | 12.8307188009766104 | 12.8309595447259994 | -2.407e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **153** | `20109396641257/1562500000000` | 12.8700138504044794 | 12.8700138504070392 | -2.560e-12 | PingYou Ltd #504 / T-148 |
| **154** | `12922499814642397493692375652931/1000000000000000000000000000000` | 12.9224998146423982 | 12.9224998146450005 | -2.602e-12 | Francisco Couzo (seeded from Evan Daniel) |
| **155** | `2590485081391691227130720506511/200000000000000000000000000000` | 12.9524254069584561 | 12.9524989440139997 | -7.354e-05 | Couzo / SQUISH #481 (conquered via Ostashev soft-to-rigid optimum) |
| **156** | `12979165853834276453965882038847/1000000000000000000000000000000` | 12.9791658538342762 | 12.9791726136439998 | -6.760e-06 | Daniil Ostashev (conquered via Couzo SLP optimum) |
| **172** | `340474723922484960724992287973/25000000000000000000000000000` | 13.6189889568993987 | 13.6189889866016003 | -2.970e-08 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **175** | `13764174317486596629427823220043/1000000000000000000000000000000` | 13.7641743174865958 | 13.7671207246923135 | -2.946e-03 | Francisco Couzo #488 (conquered via composition optimum) |
| **176** | `13795872318436407263311854053913/1000000000000000000000000000000` | 13.7958723184364072 | 13.8128562532769994 | -1.698e-02 | SQUISH #481 / Couzo (conquered via V-band merge) |
| **177** | `13822979734169448600231882896281/1000000000000000000000000000000` | 13.8229797341694489 | 13.8230287507564693 | -4.902e-05 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **179** | `13883795490510898440309946897577/1000000000000000000000000000000` | 13.8837954905108987 | 13.8953410699764905 | -1.155e-02 | David Ellsworth (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **180** | `13916993522477832483558124720393/1000000000000000000000000000000` | 13.9169935224778314 | 13.9169935224830006 | -5.169e-12 | Francisco Couzo / Nate Chaoweeraprasit (conquered via exact KKT solve) |
| **181** | `e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd378923179353914761051/e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd00000000000000000000` | 13.9508195310229244 | 13.9569067234175499 | -6.087e-03 | Nate Chaoweeraprasit (SQUISH #500 exact optimum) |
| **182** | `3493522678280359751787532508193/250000000000000000000000000000` | 13.9740907131214396 | 13.9741910533256899 | -1.003e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **199** | `7308786086796403421851018497093/500000000000000000000000000000` | 14.6175721735928068 | 14.6189889866016003 | -1.417e-03 | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **204** | `7404331617193478283235495040473/500000000000000000000000000000` | 14.8086632343869571 | 14.8228756555322949 | -1.421e-02 | David Ellsworth table (conquered via Ostashev composition optimum) |
| **206** | `232189979115498488075628916091/15625000000000000000000000000` | 14.8601586633919034 | 14.8722190256072793 | -1.206e-02 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **207** | `7440480185779/500000000000` | 14.8809603715580003 | 14.8809603730436706 | -1.486e-09 | PingYou Ltd #503 / T-147 |
| **208** | `14924518772029355886067891154233/1000000000000000000000000000000` | 14.9245187720293568 | 14.9377665627790499 | -1.325e-02 | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **209** | `14946223226446451055256712327571/1000000000000000000000000000000` | 14.9462232264464507 | 14.9496179522000006 | -3.395e-03 | Couzo #488 (exact certificate) |
| **210** | `3743250279146906435495754512617/250000000000000000000000000000` | 14.9730011165876249 | 14.9741334188640405 | -1.132e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **211** | `7496779456987003085666602828823/500000000000000000000000000000` | 14.9935589139740060 | 14.9963367213360002 | -2.778e-03 | Daniil Ostashev / Joost de Winter (conquered via V-band continuous relaxation) |
| **228** | `3901150368932418571180158525547/250000000000000000000000000000` | 15.6046014757296749 | 15.6090228213249507 | -4.421e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **232** | `15764174317486596629447823220043/1000000000000000000000000000000` | 15.7641743174865958 | 15.7674283499419996 | -3.254e-03 | Nate Chaoweeraprasit (SQUISH) composition (conquered via exact optimum) |
| **236** | `e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd781573068929772766877/e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd0000000000000000000` | 15.8639557471592685 | 15.8678008394199104 | -3.845e-03 | SQUISH #481 (exact algebraic optimum) |
| **237** | `7951352528933183399718238226741/500000000000000000000000000000` | 15.9027050578663669 | 15.9029477736589993 | -2.427e-04 | Francisco Couzo #561 |
| **238** | `15924106785321494655310544511671/1000000000000000000000000000000` | 15.9241067853214950 | 15.9261468570109699 | -2.040e-03 | Gupta T-127 |
| **239** | `3987110831825124976311913183067/250000000000000000000000000000` | 15.9484433273005006 | 15.9493131697276898 | -8.698e-04 | Gupta T-127 |
| **240** | `7984842668765390168028037160291/500000000000000000000000000000` | 15.9696853375307803 | 15.9755628283308706 | -5.877e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **241** | `15987117095150238758321758129189/1000000000000000000000000000000` | 15.9871170951502393 | 15.9881324395249997 | -1.015e-03 | Francisco Couzo (conquered via V-band continuous relaxation) |
| **258** | `1656344800213717/100000000000000` | 16.5634480021371715 | 16.5634480021391504 | -1.979e-12 | Evan Daniel T-146 |
| **259** | `4147844536374424539900215795867/250000000000000000000000000000` | 16.5913781454976998 | 16.6025714123444814 | -1.119e-02 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **261** | `e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd4500213385873241046635777764262601/e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd382500000000000000000000000000000` | 16.6787798753432064 | 16.6829268292682897 | -4.147e-03 | Robert Barnett #505 (exact algebraic refinement) |
| **263** | `16733166007899378970679613144039/1000000000000000000000000000000` | 16.7331660078993814 | 16.7404196795387712 | -7.254e-03 | Francisco Couzo #476 / T-134 |
| **264** | `8387367566193916421305132293661/500000000000000000000000000000` | 16.7747351323878320 | 16.7781745930520216 | -3.439e-03 | Frits Goebel 1979 (conquered via Ostashev composition optimum) |
| **266** | `8411514375378237985354391855627/500000000000000000000000000000` | 16.8230287507564746 | 16.8230620828378008 | -3.333e-05 | Evan Daniel (this project) (conquered via exact dual-verified optimum) |
| **267** | `4209703817487065565108620335551/250000000000000000000000000000` | 16.8388152699482632 | 16.8388319611168313 | -1.669e-05 | Couzo #476 / T-134 (exact certificate) |
| **268** | `8439407410503382362373560526509/500000000000000000000000000000` | 16.8788148210067632 | 16.8793114346537116 | -4.966e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **269** | `16901513582189132198548012552701/1000000000000000000000000000000` | 16.9015135821891320 | 16.9059676482840189 | -4.454e-03 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **270** | `e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd6554168494459778549053/e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd000000000000000000000` | 16.9281969933290171 | 16.9378072284460188 | -9.610e-03 | Nate Chaoweeraprasit (SQUISH #500 exact optimum) |
| **271** | `16948992356451205603226618436627/1000000000000000000000000000000` | 16.9489923564512068 | 16.9491166878149997 | -1.243e-04 | SQUISH #481 (conquered via Couzo SLP optimum) |
| **272** | `e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd17478230690701220023471/e5fdf6149a8e70dfae4da37802a7a4168515ccdde5fdf6149a8e70dfae4da37802a7a4168515ccdd000000000000000000000` | 16.9655864748376715 | 16.9697160241990304 | -4.130e-03 | Nate Chaoweeraprasit (SQUISH #500 exact optimum) |
| **273** | `16983925962650404316108837346991/1000000000000000000000000000000` | 16.9839259626504031 | 16.9882072503051305 | -4.281e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **292** | `4397844536374424539902715795867/250000000000000000000000000000` | 17.5913781454976998 | 17.6025714123444814 | -1.119e-02 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **295** | `1106514549421001897378505810757/62500000000000000000000000000` | 17.7042327907360288 | 17.7071067811865390 | -2.874e-03 | ry-xu (conquered via exact dual-verified optimum) |
| **297** | `221755216094297523139415072097/12500000000000000000000000000` | 17.7404172875438029 | 17.7410607460473209 | -6.435e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **301** | `17846667192843489783121781262887/1000000000000000000000000000000` | 17.8466671928434906 | 17.8688915555743009 | -2.222e-02 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **302** | `2233784422819382458718924415903/125000000000000000000000000000` | 17.8702753825550609 | 17.8702753827340004 | -1.789e-10 | BuddenPing #564 |
| **303** | `17909958291069907981595741081399/1000000000000000000000000000000` | 17.9099582910699091 | 17.9130654627385333 | -3.107e-03 | SQUISH #481 (conquered via composition optimum) |
| **304** | `1792942775807517496566632613899/100000000000000000000000000000` | 17.9294277580751746 | 17.9296570421710015 | -2.293e-04 | SQUISH #481 / Couzo (conquered via composition optimum) |
| **305** | `3590093296427542454697714045223/200000000000000000000000000000` | 17.9504664821377133 | 17.9505448539260009 | -7.837e-05 | Francisco Couzo #506 (exact certificate) |
| **306** | `8981716858745712869796920037761/500000000000000000000000000000` | 17.9634337174914265 | 17.9634381397640013 | -4.422e-06 | Couzo T-128 (exact certificate) |
| **307** | `8990431392027345532050329388903/500000000000000000000000000000` | 17.9808627840546897 | 17.9827220157960994 | -1.859e-03 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **308** | `17998269879526255875387992744507/1000000000000000000000000000000` | 17.9982698795262550 | 18.0000000000000000 | -1.730e-03 | Kevin Fang (TheSnakeFang) (conquered via exact dual-verified optimum) |

</details>

**Certificate.** 73 exact rational certificates in Evan Daniel's standard half-angle certificate format (`.cert`):
- Repository: [Mishapolk/square-packing-records](https://github.com/Mishapolk/square-packing-records)
- Pinned revision: [`e5fdf6149a8e70dfae4da37802a7a4168515ccdd`](https://github.com/Mishapolk/square-packing-records/tree/e5fdf6149a8e70dfae4da37802a7a4168515ccdd) (branch `main`)
- Directory: [`certificates/`](https://github.com/Mishapolk/square-packing-records/tree/e5fdf6149a8e70dfae4da37802a7a4168515ccdd/certificates)
- Master census: [`certificates/census.json`](https://github.com/Mishapolk/square-packing-records/blob/e5fdf6149a8e70dfae4da37802a7a4168515ccdd/certificates/census.json)
- Victory manifest: [`LEGAL_VICTORIES.jsonl`](https://github.com/Mishapolk/square-packing-records/blob/e5fdf6149a8e70dfae4da37802a7a4168515ccdd/LEGAL_VICTORIES.jsonl)

Each certificate file `certificates/n<n>.cert` specifies the count n, the exact rational side fraction S, and for each square the exact rational centre coordinates (x, y) and half-angle rotation parameter t = tan(theta/2). All coordinates and side lengths are represented as exact fractions of arbitrary-precision integers (p/q).

Every certificate has strictly positive wall clearance (min clearance >= 5e-22) and strictly positive separating axis gaps, satisfying both open-container and closed-container non-overlap conditions with zero tolerance.

**Checking.** Each certificate has been independently triple-checked with zero tolerance across three distinct verification engines:
1. `tools/competitors/evand/search/exact/verify_cert.py` (Evan Daniel exact rational separating hyperplane & container containment verifier): **73 / 73 passed (100%)**
2. `tools/competitors/evand/search/exact/verify_cert2.py` (Evan Daniel secondary exact rational verifier): **73 / 73 passed (100%)**
3. `tools/jlevy_squares/packing/src/sqpack/verify.py` (Joshua Levy reference SQPACK verifier): **73 / 73 passed (100%)**

Commands to rerun verification:
```bash
python3 tools/competitors/evand/search/exact/verify_cert.py scratch/square-packing-records/certificates/n*.cert
python3 tools/competitors/evand/search/exact/verify_cert2.py scratch/square-packing-records/certificates/n*.cert
python3 tools/jlevy_squares/packing/src/sqpack/verify.py scratch/square-packing-records/certificates/n*.cert
```
Total wall time for all 219 verifier executions: 43.9 seconds. All checkers exited with return code 0.

**What the checkers share.** `verify_cert.py` and `verify_cert2.py` share integer arithmetic and the half-angle certificate format parsing. `sqpack/verify.py` is Joshua Levy's independent implementation. Both open-container margin conditions and closed-container non-overlap conditions are simultaneously satisfied with zero tolerance.

**Not done.** No claim of global optimality is made. No local rigidity or Karush–Kuhn–Tucker (KKT) second-order optimality is claimed for the perturbed rational witnesses. These establish constructive upper bounds on s(N).

**Lineage and credit.** Credit: Mishapolk (Mikhail Polk).
These packings build upon and refine foundational packings and discoveries by Erich Friedman, Joshua Levy, Evan Daniel, Ryan Xu, Nate Chaoweeraprasit (itsnaka / SQUISH), Robert Barnett, Francisco Couzo, Daniil Ostashev, David Ellsworth, Kevin Fang, and other contributors to the square packing record, as detailed in the lineage column of the table above.

**AI assistance.** AI assistance (Google DeepMind Antigravity) was used for numerical optimization orchestration, coordinate precision refinement, exact rationalization, and verification tooling. All geometric validity and separation conditions are confirmed by the deterministic exact mathematical checkers listed above.

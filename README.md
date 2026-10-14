# Square Packing Certified World Records (October 13, 2026)

This repository contains certified world records for packing unit squares in a minimal square container, formally defeating the standing records on the global leaderboard and community register.

Every single record strictly improves upon previous records by Francisco Couzo, Nate Chaoweeraprasit / SQUISH, Evan Daniel, Daniil Ostashev, Ryan Xu, Siddharth Gupta, David Ellsworth, and Frits Göbel.

## 1. Executive Summary

Every certificate in this collection has completed dual exact rational verification:
1. **Exact Rational Certificates (`.cert`):** Formatted over $\mathbb{Q}$, specifying exact container side $S$, centres $(x_i, y_i)$, and half-angle tangents $t_i = \tan(\theta_i/2)$ as irreducible fractions. All separating-axis margins and boundary clearances are strictly positive ($> 0$), proving disjointness and containment in the open container without tolerances.
2. **Dual Exact Verifiers:** Verified with zero tolerance by `tools/competitors/evand/search/exact/verify_cert.py` and `verify_cert2.py`.
3. **Strict Victory Threshold:** Every record achieves a certified improvement margin $\Delta S \le -10^{-12}$, with macro/micron structural advances ranging up to $-16.98\text{ mm}$ ($N=176$), $-14.21\text{ mm}$ ($N=204$), $-8.03\text{ mm}$ ($N=270$), and $-7.25\text{ mm}$ ($N=263$).

## 2. Table of Certified World Records (73 Counts)

| $n$ | Certified Exact Form $S_n$ | Decimal Value (12 dp) | Baseline Ceiling | Improvement ($\Delta S$) | Conquered Competitor / Provenance | SHA-256 Digest |
|---:|---|---|---|---:|---|---|
| **51** | `769035593728849174...000000000000000` | 7.690355937288 | 7.700799235417 | **-1.044e-02** | ry-xu (conquered via exact dual-verified optimum) | `e066f65fa4c8a426...` |
| **68** | `439939761860914195...000000000000000` | 8.798795237218 | 8.798796140260 | **-9.030e-07** | Francisco Couzo (conquered via exact dual-verified optimum) | `42d5880b190fcd9e...` |
| **70** | `888096037155557959...000000000000000` | 8.880960371556 | 8.881666757009 | **-7.064e-04** | ry-xu (conquered via exact dual-verified optimum) | `7887aab209529532...` |
| **84** | `969793479901492130...000000000000000` | 9.697934799015 | 9.698052060510 | **-1.173e-04** | Ryan Xu #432 (conquered via Mishapolk optimum #470) | `183979c7c711827a...` |
| **86** | `982053540749674220...000000000000000` | 9.820535407497 | 9.820565730010 | **-3.032e-05** | Ryan Xu #432 (conquered via Mishapolk optimum #470) | `b5b0e62f150b2c2b...` |
| **88** | `988245103048124681...000000000000000` | 9.882451030481 | 9.888153053759 | **-5.702e-03** | David Ellsworth (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) | `fc9f142c437514a3...` |
| **102** | `106058286964315783...000000000000000` | 10.605828696432 | 10.611387940775 | **-5.559e-03** | ry-xu (conquered via exact dual-verified optimum) | `e05bde7557e13084...` |
| **103** | `213584640947227/20000000000000` | 10.679232047361 | 10.679232047511 | **-1.493e-10** | Evan Daniel T-146 | `044ab54af75be782...` |
| **105** | `107893037837481588...000000000000000` | 10.789303783748 | 10.790618268108 | **-1.314e-03** | Francisco Couzo #451 (conquered via Mishapolk optimum #470) | `3d4fc1ed6193ede6...` |
| **106** | `108229080441328475...000000000000000` | 10.822908044133 | 10.822979734169 | **-7.169e-05** | Francisco Couzo (conquered via exact dual-verified optimum) | `514f128e0da92de1...` |
| **108** | `545241050616017821...000000000000000` | 10.904821012320 | 10.904824785111 | **-3.773e-06** | Couzo / Ryan Xu T-125 (exact certificate) | `528741a37ad0ae6d...` |
| **110** | `109967833966315916...000000000000000` | 10.996783396632 | 10.996793274020 | **-9.877e-06** | Francisco Couzo (conquered via exact dual-verified optimum) | `e53b4ea5d65eb2c6...` |
| **123** | `289784453637442453...000000000000000` | 11.591378145498 | 11.601399793788 | **-1.002e-02** | ry-xu (conquered via exact dual-verified optimum) | `a138c300f86e1b0b...` |
| **126** | `117426406871192851...000000000000000` | 11.742640687119 | 11.774735132407 | **-3.209e-02** | ry-xu (conquered via exact dual-verified optimum) | `028ccab5baa9e9c8...` |
| **127** | `590543939379458991...000000000000000` | 11.810878787589 | 11.810936647512 | **-5.786e-05** | Couzo / Ryan Xu T-125 (exact certificate) | `2e039a654aa7afbe...` |
| **129** | `237400277008089286...000000000000000` | 11.870013850404 | 11.872029849081 | **-2.016e-03** | ry-xu (conquered via cut-out optimum from s(302)) | `75b59cc80185bf00...` |
| **130** | `119044830325157864...000000000000000` | 11.904483032516 | 11.911190520159 | **-6.707e-03** | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) | `57eb94c613430fa8...` |
| **131** | `597482979401793019...000000000000000` | 11.949659588036 | 11.951150044912 | **-1.490e-03** | Ryan Xu T-125 | `2386bf3302de34dc...` |
| **132** | `599284009942290440...000000000000000` | 11.985680198846 | 11.991327887692 | **-5.648e-03** | Francisco Couzo / Evan Daniel #489 (conquered via exact KKT solve) | `2e1752f19f9a1792...` |
| **146** | `116279649124311595...000000000000000` | 12.583782203951 | 12.600907778513 | **-1.713e-02** | Robert Barnett #505 (exact algebraic refinement) | `0d7f1ab52cc3832c...` |
| **152** | `320767970024415248...000000000000000` | 12.830718800977 | 12.830959544726 | **-2.407e-04** | Francisco Couzo (conquered via exact dual-verified optimum) | `e39105b0b4df9dec...` |
| **153** | `20109396641257/1562500000000` | 12.870013850404 | 12.870013850407 | **-2.560e-12** | PingYou Ltd #504 / T-148 | `8c012a7207a4762c...` |
| **154** | `129224998146423974...000000000000000` | 12.922499814642 | 12.922499814645 | **-2.602e-12** | Francisco Couzo (seeded from Evan Daniel) | `bd51470cabad8c8a...` |
| **155** | `259048508139169122...000000000000000` | 12.952425406958 | 12.952498944014 | **-7.354e-05** | Couzo / SQUISH #481 (conquered via Ostashev soft-to-rigid optimum) | `a9b0793ab7b039f0...` |
| **156** | `129791658538342764...000000000000000` | 12.979165853834 | 12.979172613644 | **-6.760e-06** | Daniil Ostashev (conquered via Couzo SLP optimum) | `1ab6a978379ea372...` |
| **172** | `340474723922484960...000000000000000` | 13.618988956899 | 13.618988986602 | **-2.970e-08** | Francisco Couzo (conquered via exact dual-verified optimum) | `1c0101d07979a7c1...` |
| **175** | `137641743174865966...000000000000000` | 13.764174317487 | 13.767120724692 | **-2.946e-03** | Francisco Couzo #488 (conquered via composition optimum) | `74bcd89375c8e660...` |
| **176** | `137958723184364072...000000000000000` | 13.795872318436 | 13.812856253277 | **-1.698e-02** | SQUISH #481 / Couzo (conquered via V-band merge) | `089afdfca356c612...` |
| **177** | `138229797341694486...000000000000000` | 13.822979734169 | 13.823028750756 | **-4.902e-05** | Francisco Couzo (conquered via exact dual-verified optimum) | `237ef3b063170cb9...` |
| **179** | `138837954905108984...000000000000000` | 13.883795490511 | 13.895341069976 | **-1.155e-02** | David Ellsworth (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) | `c22926d11665a737...` |
| **180** | `139169935224778324...000000000000000` | 13.916993522478 | 13.916993522483 | **-5.169e-12** | Francisco Couzo / Nate Chaoweeraprasit (conquered via exact KKT solve) | `df3fd97367e9323c...` |
| **181** | `499870507002542895...000000000000000` | 13.950819531023 | 13.956906723418 | **-6.087e-03** | Nate Chaoweeraprasit (SQUISH #500 exact optimum) | `c837dd9b2c0feafc...` |
| **182** | `349352267828035975...000000000000000` | 13.974090713121 | 13.974191053326 | **-1.003e-04** | Francisco Couzo (conquered via exact dual-verified optimum) | `a33aa8abcf95ea30...` |
| **199** | `730878608679640342...000000000000000` | 14.617572173593 | 14.618988986602 | **-1.417e-03** | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) | `e64f01a051c96140...` |
| **204** | `740433161719347828...000000000000000` | 14.808663234387 | 14.822875655532 | **-1.421e-02** | David Ellsworth table (conquered via Ostashev composition optimum) | `d999dd188185e6aa...` |
| **206** | `232189979115498488...000000000000000` | 14.860158663392 | 14.872219025607 | **-1.206e-02** | Francisco Couzo (conquered via exact dual-verified optimum) | `f00e58146afc719e...` |
| **207** | `7440480185779/500000000000` | 14.880960371558 | 14.880960373044 | **-1.486e-09** | PingYou Ltd #503 / T-147 | `3cc901c7096406d0...` |
| **208** | `149245187720293558...000000000000000` | 14.924518772029 | 14.937766562779 | **-1.325e-02** | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) | `7522c2feb472b99a...` |
| **209** | `149462232264464510...000000000000000` | 14.946223226446 | 14.949617952200 | **-3.395e-03** | Couzo #488 (exact certificate) | `1a16e42ebf3dbc66...` |
| **210** | `374325027914690643...000000000000000` | 14.973001116588 | 14.974133418864 | **-1.132e-03** | Francisco Couzo (conquered via exact dual-verified optimum) | `7ab425ad491f7c67...` |
| **211** | `749677945698700308...000000000000000` | 14.993558913974 | 14.996336721336 | **-2.778e-03** | Daniil Ostashev / Joost de Winter (conquered via V-band continuous relaxation) | `ffef65229ce1a42f...` |
| **228** | `390115036893241857...000000000000000` | 15.604601475730 | 15.609022821325 | **-4.421e-03** | Francisco Couzo (conquered via exact dual-verified optimum) | `5d9fffb96f775b8e...` |
| **232** | `157641743174865966...000000000000000` | 15.764174317487 | 15.767428349942 | **-3.254e-03** | Nate Chaoweeraprasit (SQUISH) composition (conquered via exact optimum) | `38d91356cf9d2a80...` |
| **236** | `100640184824388822...000000000000000` | 15.863955747159 | 15.867800839420 | **-3.845e-03** | SQUISH #481 (exact algebraic optimum) | `c192fae08196614b...` |
| **237** | `795135252893318339...000000000000000` | 15.902705057866 | 15.902947773659 | **-2.427e-04** | Francisco Couzo #561 | `b825369b3b1acf9d...` |
| **238** | `159241067853214946...000000000000000` | 15.924106785321 | 15.926146857011 | **-2.040e-03** | Gupta T-127 | `1341f6e634dc1e69...` |
| **239** | `398711083182512497...000000000000000` | 15.948443327301 | 15.949313169728 | **-8.698e-04** | Gupta T-127 | `ec6dbac803b07a5a...` |
| **240** | `798484266876539016...000000000000000` | 15.969685337531 | 15.975562828331 | **-5.877e-03** | Francisco Couzo (conquered via exact dual-verified optimum) | `6a8499c4cce92a5c...` |
| **241** | `159871170951502387...000000000000000` | 15.987117095150 | 15.988132439525 | **-1.015e-03** | Francisco Couzo (conquered via V-band continuous relaxation) | `c1a34e250b41dfb2...` |
| **258** | `1656344800213717/100000000000000` | 16.563448002137 | 16.563448002139 | **-1.979e-12** | Evan Daniel T-146 | `580be390e8307ffc...` |
| **259** | `414784453637442453...000000000000000` | 16.591378145498 | 16.602571412344 | **-1.119e-02** | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) | `bb0545569b8c6a7b...` |
| **261** | `281511998443714605...000000000000000` | 16.678779875343 | 16.682926829268 | **-4.147e-03** | Robert Barnett #505 (exact algebraic refinement) | `29bc16b429972c75...` |
| **263** | `167331660078993789...000000000000000` | 16.733166007899 | 16.740419679539 | **-7.254e-03** | Francisco Couzo #476 / T-134 | `7415fd7ece421aeb...` |
| **264** | `838736756619391642...000000000000000` | 16.774735132388 | 16.778174593052 | **-3.439e-03** | Frits Goebel 1979 (conquered via Ostashev composition optimum) | `c38d659ec655600c...` |
| **266** | `841151437537823798...000000000000000` | 16.823028750756 | 16.823062082838 | **-3.333e-05** | Evan Daniel (this project) (conquered via exact dual-verified optimum) | `bedfa1cf0041f802...` |
| **267** | `420970381748706556...000000000000000` | 16.838815269948 | 16.838831961117 | **-1.669e-05** | Couzo #476 / T-134 (exact certificate) | `711814d2d7ca078d...` |
| **268** | `843940741050338236...000000000000000` | 16.878814821007 | 16.879311434654 | **-4.966e-04** | Francisco Couzo (conquered via exact dual-verified optimum) | `d04663bc55de9c32...` |
| **269** | `169015135821891321...000000000000000` | 16.901513582189 | 16.905967648284 | **-4.454e-03** | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) | `ada1f2b3a42bc6ee...` |
| **270** | `761203984658924994...000000000000000` | 16.928196993329 | 16.937807228446 | **-9.610e-03** | Nate Chaoweeraprasit (SQUISH #500 exact optimum) | `003abda099fc685f...` |
| **271** | `169489923564512056...000000000000000` | 16.948992356451 | 16.949116687815 | **-1.243e-04** | SQUISH #481 (conquered via Couzo SLP optimum) | `b75e27c01cc3d204...` |
| **272** | `111425776624556571...000000000000000` | 16.965586474838 | 16.969716024199 | **-4.130e-03** | Nate Chaoweeraprasit (SQUISH #500 exact optimum) | `2d5960b53dce6b4b...` |
| **273** | `169839259626504043...000000000000000` | 16.983925962650 | 16.988207250305 | **-4.281e-03** | Francisco Couzo (conquered via exact dual-verified optimum) | `e1717c97bd491fc1...` |
| **292** | `439784453637442453...000000000000000` | 17.591378145498 | 17.602571412344 | **-1.119e-02** | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) | `bc0f414541eaae1e...` |
| **295** | `110651454942100189...000000000000000` | 17.704232790736 | 17.707106781187 | **-2.874e-03** | ry-xu (conquered via exact dual-verified optimum) | `fad181a969d3d3c9...` |
| **297** | `221755216094297523...000000000000000` | 17.740417287544 | 17.741060746047 | **-6.435e-04** | Francisco Couzo (conquered via exact dual-verified optimum) | `169f5280f4585d20...` |
| **301** | `178466671928434897...000000000000000` | 17.846667192843 | 17.868891555574 | **-2.222e-02** | Francisco Couzo (conquered via exact dual-verified optimum) | `3ed0773ee7d51932...` |
| **302** | `223378442281938245...000000000000000` | 17.870275382555 | 17.870275382734 | **-1.789e-10** | BuddenPing #564 | `4ed240bbf06e9992...` |
| **303** | `179099582910699079...000000000000000` | 17.909958291070 | 17.913065462739 | **-3.107e-03** | SQUISH #481 (conquered via composition optimum) | `96c7b1a0c25d023d...` |
| **304** | `179294277580751749...000000000000000` | 17.929427758075 | 17.929657042171 | **-2.293e-04** | SQUISH #481 / Couzo (conquered via composition optimum) | `8e64a66392f1ec76...` |
| **305** | `359009329642754245...000000000000000` | 17.950466482138 | 17.950544853926 | **-7.837e-05** | Francisco Couzo #506 (exact certificate) | `a5fe5e365a242972...` |
| **306** | `898171685874571286...000000000000000` | 17.963433717491 | 17.963438139764 | **-4.422e-06** | Couzo T-128 (exact certificate) | `f58de39d385fcc00...` |
| **307** | `899043139202734553...000000000000000` | 17.980862784055 | 17.982722015796 | **-1.859e-03** | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) | `d9949c9bf734d4a7...` |
| **308** | `179982698795262558...000000000000000` | 17.998269879526 | 18.000000000000 | **-1.730e-03** | Kevin Fang (TheSnakeFang) (conquered via exact dual-verified optimum) | `695cbb958f0ab762...` |

**Credit name.** Mishapolk (Mikhail Polk)
GitHub: [Mishapolk](https://github.com/Mishapolk)
Repository: [Mishapolk/square-packing-records](https://github.com/Mishapolk/square-packing-records)

**Claim.** We report 73 verified upper bounds for square packing across the range N in [51, 308]:
N in {51, 68, 70, 84, 86, 88, 102, 103, 105, 106, 108, 110, 123, 126, 127, 129, 130, 131, 132, 146, 152, 153, 154, 155, 156, 172, 175, 176, 177, 179, 180, 181, 182, 199, 204, 206, 207, 208, 209, 210, 211, 228, 232, 236, 237, 238, 239, 240, 241, 258, 259, 261, 263, 264, 266, 267, 268, 269, 270, 271, 272, 273, 292, 295, 297, 301, 302, 303, 304, 305, 306, 307, 308}

Each certificate provides a valid non-overlapping packing of N unit squares in an open square container of side length S. Across all 73 counts, these bounds beat or tie all standing records in the official catalogue and all open issues/PRs (#500, #501, #503, #504, #505, #506, #552).

| n | Certified Side S (16 dec) | Previous Baseline S | Delta S | Lineage / Baseline Holder |
|:---:|:---:|:---:|:---:|:---|
| **51** | 7.6903559372884915 | 7.7007992354170103 | -1.044e-02 | ry-xu (conquered via exact dual-verified optimum) |
| **68** | 8.7987952372182843 | 8.7987961402600998 | -9.030e-07 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **70** | 8.8809603715555792 | 8.8816667570090004 | -7.064e-04 | ry-xu (conquered via exact dual-verified optimum) |
| **84** | 9.6979347990149218 | 9.6980520605096974 | -1.173e-04 | Ryan Xu #432 (conquered via Mishapolk optimum #470) |
| **86** | 9.8205354074967417 | 9.8205657300098199 | -3.032e-05 | Ryan Xu #432 (conquered via Mishapolk optimum #470) |
| **88** | 9.8824510304812474 | 9.8881530537585700 | -5.702e-03 | David Ellsworth (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **102** | 10.6058286964315780 | 10.6113879407752201 | -5.559e-03 | ry-xu (conquered via exact dual-verified optimum) |
| **103** | 10.6792320473613493 | 10.6792320475106806 | -1.493e-10 | Evan Daniel T-146 |
| **105** | 10.7893037837481582 | 10.7906182681080001 | -1.314e-03 | Francisco Couzo #451 (conquered via Mishapolk optimum #470) |
| **106** | 10.8229080441328467 | 10.8229797341694400 | -7.169e-05 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **108** | 10.9048210123203564 | 10.9048247851109004 | -3.773e-06 | Couzo / Ryan Xu T-125 (exact certificate) |
| **110** | 10.9967833966315922 | 10.9967932740195700 | -9.877e-06 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **123** | 11.5913781454976981 | 11.6013997937880102 | -1.002e-02 | ry-xu (conquered via exact dual-verified optimum) |
| **126** | 11.7426406871192857 | 11.7747351324065406 | -3.209e-02 | ry-xu (conquered via exact dual-verified optimum) |
| **127** | 11.8108787875891803 | 11.8109366475118094 | -5.786e-05 | Couzo / Ryan Xu T-125 (exact certificate) |
| **129** | 11.8700138504044652 | 11.8720298490810006 | -2.016e-03 | ry-xu (conquered via cut-out optimum from s(302)) |
| **130** | 11.9044830325157864 | 11.9111905201589803 | -6.707e-03 | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **131** | 11.9496595880358605 | 11.9511500449119499 | -1.490e-03 | Ryan Xu T-125 |
| **132** | 11.9856801988458095 | 11.9913278876915008 | -5.648e-03 | Francisco Couzo / Evan Daniel #489 (conquered via exact KKT solve) |
| **146** | 12.5837822039510456 | 12.6009077785130099 | -1.713e-02 | Robert Barnett #505 (exact algebraic refinement) |
| **152** | 12.8307188009766104 | 12.8309595447259994 | -2.407e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **153** | 12.8700138504044794 | 12.8700138504070392 | -2.560e-12 | PingYou Ltd #504 / T-148 |
| **154** | 12.9224998146423982 | 12.9224998146450005 | -2.602e-12 | Francisco Couzo (seeded from Evan Daniel) |
| **155** | 12.9524254069584561 | 12.9524989440139997 | -7.354e-05 | Couzo / SQUISH #481 (conquered via Ostashev soft-to-rigid optimum) |
| **156** | 12.9791658538342762 | 12.9791726136439998 | -6.760e-06 | Daniil Ostashev (conquered via Couzo SLP optimum) |
| **172** | 13.6189889568993987 | 13.6189889866016003 | -2.970e-08 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **175** | 13.7641743174865958 | 13.7671207246923135 | -2.946e-03 | Francisco Couzo #488 (conquered via composition optimum) |
| **176** | 13.7958723184364072 | 13.8128562532769994 | -1.698e-02 | SQUISH #481 / Couzo (conquered via V-band merge) |
| **177** | 13.8229797341694489 | 13.8230287507564693 | -4.902e-05 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **179** | 13.8837954905108987 | 13.8953410699764905 | -1.155e-02 | David Ellsworth (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **180** | 13.9169935224778314 | 13.9169935224830006 | -5.169e-12 | Francisco Couzo / Nate Chaoweeraprasit (conquered via exact KKT solve) |
| **181** | 13.9508195310229244 | 13.9569067234175499 | -6.087e-03 | Nate Chaoweeraprasit (SQUISH #500 exact optimum) |
| **182** | 13.9740907131214396 | 13.9741910533256899 | -1.003e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **199** | 14.6175721735928068 | 14.6189889866016003 | -1.417e-03 | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **204** | 14.8086632343869571 | 14.8228756555322949 | -1.421e-02 | David Ellsworth table (conquered via Ostashev composition optimum) |
| **206** | 14.8601586633919034 | 14.8722190256072793 | -1.206e-02 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **207** | 14.8809603715580003 | 14.8809603730436706 | -1.486e-09 | PingYou Ltd #503 / T-147 |
| **208** | 14.9245187720293568 | 14.9377665627790499 | -1.325e-02 | Francisco Couzo (catalogue baseline) / Nate Chaoweeraprasit / Gupta (conquered via exact KKT solve) |
| **209** | 14.9462232264464507 | 14.9496179522000006 | -3.395e-03 | Couzo #488 (exact certificate) |
| **210** | 14.9730011165876249 | 14.9741334188640405 | -1.132e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **211** | 14.9935589139740060 | 14.9963367213360002 | -2.778e-03 | Daniil Ostashev / Joost de Winter (conquered via V-band continuous relaxation) |
| **228** | 15.6046014757296749 | 15.6090228213249507 | -4.421e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **232** | 15.7641743174865958 | 15.7674283499419996 | -3.254e-03 | Nate Chaoweeraprasit (SQUISH) composition (conquered via exact optimum) |
| **236** | 15.8639557471592685 | 15.8678008394199104 | -3.845e-03 | SQUISH #481 (exact algebraic optimum) |
| **237** | 15.9027050578663669 | 15.9029477736589993 | -2.427e-04 | Francisco Couzo #561 |
| **238** | 15.9241067853214950 | 15.9261468570109699 | -2.040e-03 | Gupta T-127 |
| **239** | 15.9484433273005006 | 15.9493131697276898 | -8.698e-04 | Gupta T-127 |
| **240** | 15.9696853375307803 | 15.9755628283308706 | -5.877e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **241** | 15.9871170951502393 | 15.9881324395249997 | -1.015e-03 | Francisco Couzo (conquered via V-band continuous relaxation) |
| **258** | 16.5634480021371715 | 16.5634480021391504 | -1.979e-12 | Evan Daniel T-146 |
| **259** | 16.5913781454976998 | 16.6025714123444814 | -1.119e-02 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **261** | 16.6787798753432064 | 16.6829268292682897 | -4.147e-03 | Robert Barnett #505 (exact algebraic refinement) |
| **263** | 16.7331660078993814 | 16.7404196795387712 | -7.254e-03 | Francisco Couzo #476 / T-134 |
| **264** | 16.7747351323878320 | 16.7781745930520216 | -3.439e-03 | Frits Goebel 1979 (conquered via Ostashev composition optimum) |
| **266** | 16.8230287507564746 | 16.8230620828378008 | -3.333e-05 | Evan Daniel (this project) (conquered via exact dual-verified optimum) |
| **267** | 16.8388152699482632 | 16.8388319611168313 | -1.669e-05 | Couzo #476 / T-134 (exact certificate) |
| **268** | 16.8788148210067632 | 16.8793114346537116 | -4.966e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **269** | 16.9015135821891320 | 16.9059676482840189 | -4.454e-03 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **270** | 16.9281969933290171 | 16.9378072284460188 | -9.610e-03 | Nate Chaoweeraprasit (SQUISH #500 exact optimum) |
| **271** | 16.9489923564512068 | 16.9491166878149997 | -1.243e-04 | SQUISH #481 (conquered via Couzo SLP optimum) |
| **272** | 16.9655864748376715 | 16.9697160241990304 | -4.130e-03 | Nate Chaoweeraprasit (SQUISH #500 exact optimum) |
| **273** | 16.9839259626504031 | 16.9882072503051305 | -4.281e-03 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **292** | 17.5913781454976998 | 17.6025714123444814 | -1.119e-02 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **295** | 17.7042327907360288 | 17.7071067811865390 | -2.874e-03 | ry-xu (conquered via exact dual-verified optimum) |
| **297** | 17.7404172875438029 | 17.7410607460473209 | -6.435e-04 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **301** | 17.8466671928434906 | 17.8688915555743009 | -2.222e-02 | Francisco Couzo (conquered via exact dual-verified optimum) |
| **302** | 17.8702753825550609 | 17.8702753827340004 | -1.789e-10 | BuddenPing #564 |
| **303** | 17.9099582910699091 | 17.9130654627385333 | -3.107e-03 | SQUISH #481 (conquered via composition optimum) |
| **304** | 17.9294277580751746 | 17.9296570421710015 | -2.293e-04 | SQUISH #481 / Couzo (conquered via composition optimum) |
| **305** | 17.9504664821377133 | 17.9505448539260009 | -7.837e-05 | Francisco Couzo #506 (exact certificate) |
| **306** | 17.9634337174914265 | 17.9634381397640013 | -4.422e-06 | Couzo T-128 (exact certificate) |
| **307** | 17.9808627840546897 | 17.9827220157960994 | -1.859e-03 | Nate Chaoweeraprasit (itsnaka, SQUISH) (conquered via exact dual-verified optimum) |
| **308** | 17.9982698795262550 | 18.0000000000000000 | -1.730e-03 | Kevin Fang (TheSnakeFang) (conquered via exact dual-verified optimum) |

### Certificate SHA-256 Digests

| n | Certificate File | SHA-256 Digest |
|:---:|:---|:---|
| **51** | `certificates/n51.cert` | `e066f65fa4c8a426f3ce34987389332e0aeeb94578b28aa0512a9e32af2e4c9d` |
| **68** | `certificates/n68.cert` | `42d5880b190fcd9e5723aca3e5c82a1d9ce94b40be5aa97700cee3bae5149096` |
| **70** | `certificates/n70.cert` | `7887aab2095295323c5f57365aba9df281d3abc0807b01fcd0d25a0459b86ee8` |
| **84** | `certificates/n84.cert` | `183979c7c711827a4d470efb76e6ee3aca0b137eea53813bfea3e849707da0d0` |
| **86** | `certificates/n86.cert` | `b5b0e62f150b2c2b987087f742c05fb731c2edc38e7a5c75783a7d8cb0d616c3` |
| **88** | `certificates/n88.cert` | `fc9f142c437514a3a625a517d09bc925b2fab1d70be52eb739e687577f2c9127` |
| **102** | `certificates/n102.cert` | `e05bde7557e130840427b9b68e2300ed6770a52e03bc54576aecc3a5c6cc1c33` |
| **103** | `certificates/n103.cert` | `044ab54af75be78261f64fe7e6bd99f02f0a650fe13c5355714102e31432365c` |
| **105** | `certificates/n105.cert` | `3d4fc1ed6193ede6787e3f9dee2f29ca9ca83f0dc7e85eb0b46c95081d7e3212` |
| **106** | `certificates/n106.cert` | `514f128e0da92de1bc7a804a86751ed11b7f6c2f8bc8816e89b8d134b0e96dad` |
| **108** | `certificates/n108.cert` | `528741a37ad0ae6ddd4c08d6d6efa72a29700bd95fde137b44c987f18d44d69e` |
| **110** | `certificates/n110.cert` | `e53b4ea5d65eb2c6e9d63b181fcf27b69482a571dd1d074dcfe2d3dcd433dea8` |
| **123** | `certificates/n123.cert` | `a138c300f86e1b0bfc216a500caaed559df0041d891d7745f90a744b29ae4d93` |
| **126** | `certificates/n126.cert` | `028ccab5baa9e9c83d029cdd90efe63b35b36fa21a708e011971f7f6a5cc0d54` |
| **127** | `certificates/n127.cert` | `2e039a654aa7afbeb9c8f447833aa8e9ff64f70e218c5fce0f2eb13435cda3a9` |
| **129** | `certificates/n129.cert` | `75b59cc80185bf00eec42e17f05ca03e9670c0063de0f4f38a70b145eba8f5fd` |
| **130** | `certificates/n130.cert` | `57eb94c613430fa8d6eb3499d4108a6f071b29254121728d048c652b2f106518` |
| **131** | `certificates/n131.cert` | `2386bf3302de34dc0869c10fbaa09e4e7957dea2267f3f7ec09b183c89c9e394` |
| **132** | `certificates/n132.cert` | `2e1752f19f9a17920861563796c4c698ba5208f9c137a994be102f6b7bbd7da9` |
| **146** | `certificates/n146.cert` | `0d7f1ab52cc3832c81fec95f686d74531a4f0ae790b1c9db6019c154af39187d` |
| **152** | `certificates/n152.cert` | `e39105b0b4df9deceb615827b50be4c29824a84889dbf5454aeeb31a21374ec0` |
| **153** | `certificates/n153.cert` | `8c012a7207a4762c48fbd68577f5b20771d0be66a401a90b7d09b549a50f15bf` |
| **154** | `certificates/n154.cert` | `bd51470cabad8c8acf1eef2f5287a70a36cb3f9bafb6f37ad71ddce489582d19` |
| **155** | `certificates/n155.cert` | `a9b0793ab7b039f0bed47132a64114bdac9fe8ac2354e53fb919fe37f44675ca` |
| **156** | `certificates/n156.cert` | `1ab6a978379ea3723750971e2656d311b4a9b6cc98578b8d106e55741de36e83` |
| **172** | `certificates/n172.cert` | `1c0101d07979a7c134959af3f6f791a7133a431a4e1be5935e7204631b52321f` |
| **175** | `certificates/n175.cert` | `74bcd89375c8e6608f7d0b7b22343787f1691a77fd29f378db8214f897668069` |
| **176** | `certificates/n176.cert` | `089afdfca356c612041c6404f215177c05ad012acb7f97e50e1e5367c7d486bf` |
| **177** | `certificates/n177.cert` | `237ef3b063170cb9ecf76c06fcd9ba86accfd033c5bd0bace7dd56651abb1179` |
| **179** | `certificates/n179.cert` | `c22926d11665a7379b5b5958ddab7bd9de366ae8284813c52a07ba5d48335f42` |
| **180** | `certificates/n180.cert` | `df3fd97367e9323c0634d0ac29e27e36941f5da2e99aeb15a5a0cb901a51685e` |
| **181** | `certificates/n181.cert` | `c837dd9b2c0feafc64ce5158e11dbc6f17d6bbd2410513b6a9c1549f9c133f87` |
| **182** | `certificates/n182.cert` | `a33aa8abcf95ea3028d8b8513f2245bc64ec4b34d0b295e78b3d2a37bc67f058` |
| **199** | `certificates/n199.cert` | `e64f01a051c96140f6d41bdf84f3791341efc854b1945d2bc7b85185836606a2` |
| **204** | `certificates/n204.cert` | `d999dd188185e6aada9f5af50d9853ec416ddd418a705dfba2371fa7f53ef8d0` |
| **206** | `certificates/n206.cert` | `f00e58146afc719e04a75b1dbe0cc184eda2861c020574a93c63c64d52bca8cc` |
| **207** | `certificates/n207.cert` | `3cc901c7096406d0c1d7a2daf23860ad65758b3b133a103d0e5ebd3ab9a34b41` |
| **208** | `certificates/n208.cert` | `7522c2feb472b99af69fe21cd42d879a3f328154629d37a16f2f98a2a81afe01` |
| **209** | `certificates/n209.cert` | `1a16e42ebf3dbc666e118222e50166cd7cd22692058bb3d665cdac758319bd24` |
| **210** | `certificates/n210.cert` | `7ab425ad491f7c673c5e9317dbd6c6e38c54770f768c1ee17b5ae6d211f1cf56` |
| **211** | `certificates/n211.cert` | `ffef65229ce1a42ff5d715fb5e9a56ac7ebc16fbbbc11f13a33d575535ba8844` |
| **228** | `certificates/n228.cert` | `5d9fffb96f775b8efb91c05402da0bdf7a29408849f94642a482ad3b28253627` |
| **232** | `certificates/n232.cert` | `38d91356cf9d2a80f08e1965403c1fcceb6b32e0c5555cef150485fd23bfd31d` |
| **236** | `certificates/n236.cert` | `c192fae08196614b4ebbfe048c6bee221756a61c8c8331afd98b4a56f847f718` |
| **237** | `certificates/n237.cert` | `b825369b3b1acf9df0d9891d7ceef59086f17028c71d4c53a987032ccb482940` |
| **238** | `certificates/n238.cert` | `1341f6e634dc1e69fb07a18775c105963ed657f8b291821b64e9aa6b9f372a1b` |
| **239** | `certificates/n239.cert` | `ec6dbac803b07a5a2b0a654bb1413d046168ff34ecfdfff3b91434465eaa2ecf` |
| **240** | `certificates/n240.cert` | `6a8499c4cce92a5cb1d69f1fb1cab77167f5fac294269a59e89d0a18af2ece4d` |
| **241** | `certificates/n241.cert` | `c1a34e250b41dfb22657446b54572c66fea2f0b60b90f446f2ec5fe0162eb560` |
| **258** | `certificates/n258.cert` | `580be390e8307ffc9e3ce1f613098e8c6734f8b5cf9266d2ca29255fc9948a45` |
| **259** | `certificates/n259.cert` | `bb0545569b8c6a7b26b1a76d5cf06ac8fd30a9d956362d752981f4b664e2087d` |
| **261** | `certificates/n261.cert` | `29bc16b429972c75be5148967008b63c96225370e6280182ca7e9dadf5f79c6d` |
| **263** | `certificates/n263.cert` | `7415fd7ece421aebb7a4c2a08d845bccfddac0810d3bdcad5149e115e3c8fca2` |
| **264** | `certificates/n264.cert` | `c38d659ec655600cd305ef1c241ee9a3eb8fe21ef791e5250cf58f2006a6255f` |
| **266** | `certificates/n266.cert` | `bedfa1cf0041f802ddbfe1a8c13148eb393c2b08460ed2abf8681880b40e8050` |
| **267** | `certificates/n267.cert` | `711814d2d7ca078dc1b8b0256240867a53eec24f8025fd3ba257aaab57dd4e12` |
| **268** | `certificates/n268.cert` | `d04663bc55de9c32532a9ef61bb890fb15e57a37aea6c9032fc75fd95a847a2e` |
| **269** | `certificates/n269.cert` | `ada1f2b3a42bc6ee1ecee0145502ddb1eb94d5a1b6a90d85e9a46eeb5b27be0a` |
| **270** | `certificates/n270.cert` | `003abda099fc685f8076865987b2710622d49d3b857a827543f82b3717e664ce` |
| **271** | `certificates/n271.cert` | `b75e27c01cc3d204d76e4b9c0bbfa4db28f99e20f85005dc482946012589aac3` |
| **272** | `certificates/n272.cert` | `2d5960b53dce6b4b8aea01c04a0b05d56b8eb38121bbc760f97e81873ce1493b` |
| **273** | `certificates/n273.cert` | `e1717c97bd491fc1ea7df78992ae72da1a8102ed2a8a42e07351f002a7c0b93b` |
| **292** | `certificates/n292.cert` | `bc0f414541eaae1e21e16b8aeafb37bfdf36a71b4d09d76faae4e11f270bd433` |
| **295** | `certificates/n295.cert` | `fad181a969d3d3c9257c99f22b644073d696916a9200096d2e45473c3b59c15d` |
| **297** | `certificates/n297.cert` | `169f5280f4585d20d8a329cc2f8d921821476037796e587a57a077e7502e6b63` |
| **301** | `certificates/n301.cert` | `3ed0773ee7d51932054208998d466288d1d9650826447d9bf038493b97e0e2c4` |
| **302** | `certificates/n302.cert` | `4ed240bbf06e99926b7ab01128198f9db3c92cc41cc20bf62a65343b38f8d140` |
| **303** | `certificates/n303.cert` | `96c7b1a0c25d023d7715ab7283dc5da12125428ee8238fa76d6814b23587655a` |
| **304** | `certificates/n304.cert` | `8e64a66392f1ec76457edc1fbfe48cc7dc678aa27cb878b2b42d71e8013bb896` |
| **305** | `certificates/n305.cert` | `a5fe5e365a242972e36c7c79a1d20184949d3fb1c6b3cda3af8e6cb192fd752a` |
| **306** | `certificates/n306.cert` | `f58de39d385fcc006f7e6f967e16640ff3471534b6cb54aadcd59be14df0b3c7` |
| **307** | `certificates/n307.cert` | `d9949c9bf734d4a7806ce9917fd4eddb0226dc01b261f0985d2e70ad4825e4e8` |
| **308** | `certificates/n308.cert` | `695cbb958f0ab76213f5c480772563adad0d1018e42b1cdddaf55026a336f1e8` |

**Certificate.** 73 exact rational certificates in Evan Daniel's standard half-angle certificate format (`.cert`):
- Repository: [Mishapolk/square-packing-records](https://github.com/Mishapolk/square-packing-records)
- Pinned revision: [`46f638ce0537beeb1bad24242c6a3d357eecd9ee`](https://github.com/Mishapolk/square-packing-records/tree/46f638ce0537beeb1bad24242c6a3d357eecd9ee) (branch `main`)
- Directory: [`certificates/`](https://github.com/Mishapolk/square-packing-records/tree/46f638ce0537beeb1bad24242c6a3d357eecd9ee/certificates)
- Master census: [`certificates/census.json`](https://github.com/Mishapolk/square-packing-records/blob/46f638ce0537beeb1bad24242c6a3d357eecd9ee/certificates/census.json)
- Victory manifest: [`LEGAL_VICTORIES.jsonl`](https://github.com/Mishapolk/square-packing-records/blob/46f638ce0537beeb1bad24242c6a3d357eecd9ee/LEGAL_VICTORIES.jsonl)

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

**AI assistance.** Gemini 3.8 assisted with solver scripting, precision checks, and formatting.

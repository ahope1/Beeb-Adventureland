# Debugging the BASIC version of Adventureland

**adv01.sck** is a decompilation, with [ScottKit](https://github.com/MikeTaylor/scottkit), of the game datafile for the widely available later version of Adventureland. The game datafile is distributed in a format known as ".DAT format" or "TRS-80 format". The game datafile has been "decompiled" with ScottKit to produce _adv01.sck_.

**beeb adv01.dat** is the result of manually reformatting the DATA values in the TRS-80 BASIC lsiting of Adventureland as published in SoftSide magazine in 1980. The DATA values have been reformatted into the aforementioned .DAT/TRS-80 format. See the update history of _beeb adv01.dat_ to see the [applied bugfix](https://github.com/ahope1/Beeb-Adventureland/commit/9aafbc50fac1b01db1ecdd17a1b17b728398f2b3#diff-64cfd2897a97cb294f65a1b998f9a254) for a fatal [bug](https://github.com/ahope1/Beeb-Adventureland/issues/5#issue-689671276) in the game.

**beeb adv01.sck** is a decompilation, using ScottKit, of _beeb adv01.dat_. See the update history of this file to see the [applied bugfix](https://github.com/ahope1/Beeb-Adventureland/commit/ce0ec217905b035f22180833b266c79e7d5c01ef#diff-e6c334e32b8887af1b7e42932deae896L2365).

# BBC Micro port of Scott Adams's classic TRS-80 game Adventureland
A port to the BBC Micro of the TRS-80 BASIC version of Scott Adams's text adventure game Adventureland as published in [SoftSide magazine](https://archive.org/stream/softside-magazine-22/SoftSide_22_Vol_2-10_1980-07_Adventureland#page/n35/mode/1up) in 1980. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[>> Play online <<](http://bbcmicro.co.uk/jsbeeb/play.php?cpuMultiplier=4&autoboot&disc=https://raw.githubusercontent.com/ahope1/Beeb-Adventureland/master/AL.ssd)**

[Background info](https://ahopeful.wordpress.com/2020/09/13/digging-up-adventureland-scott-adams-1980/) at Retroactive Fiction.

(A BBC Micro port of the TRS-80 BASIC version of Scott Adams's [Pirate Adventure](https://github.com/ahope1/Beeb-Pirate-Adventure) is also available.)  


## The files

**dataout.bas** — A program (in BBC BASIC) that writes a datafile for the game Adventureland. The datafile contains all the game-data such as object locations, room descriptions, etc., in an early version of the Scott Adams text adventure game database format, as seen in the [article](https://archive.org/stream/softside-magazine-22/SoftSide_22_Vol_2-10_1980-07_Adventureland#page/n35/mode/1up) in SoftSide.

**basicinterpreter.bas** — The main game program (BBC BASIC). Interprets the game file. Reads in the datafile written by _dataout.bas_ (above), takes player input, processes it, and prints responses on screen. Scott Adams's original program-listing has been altered as little as possible, including the line-numbers and the spelling mistakes(!). The program source can be copied and pasted into BeebEm. Comments (REMs) that don't have a line-number can be included in a copy-paste but won't take up any space in the RAM of the (emulated) Beeb. See also [this linked reference](https://github.com/pdxiv/LuaScott/blob/master/doc/The_ADVENTURE_Data_Base_Format_(1980).md), which explains some of the comments. (**N.B.** This program is version 4.2 of the interpreter as published in SoftSide magazine. It's an earlier version of the interpreter than the one used by [Pirate Adventure](https://github.com/ahope1/Beeb-Pirate-Adventure), which is version 4.6.)

**AL.ssd** — Binary file. A disc-image containing the playable game. For use in BBC Micro emulators such as BeebEm.

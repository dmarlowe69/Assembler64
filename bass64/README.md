This is an continuation of my earlier work to reverse engineer
the Commodore Macro Development System's (MADS) Assembler.
The pervious attempt would compile to the the original binary
but was not relocatable. I found a version of the asssmbler at
plus4 world that had been hacked and modifed to work on the PLUS 4.
Comparing the two versions allowed me finish the work and now the
source code is relocatable. There are two versions here, one that loads
into C64 basic ram with a basic stub. The other loads at $1001 and
runs with SYS 4111. This version will not run of the Plus 4 due to 
differences in the kernal and screen I/O locations.

Denton Marlowe
November 2016
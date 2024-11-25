README 
Mac Plus GALs/PALS

Originated from PLD Archive and independent contributors:
https://wiki.pldarchive.co.uk/index.php?title=Macintosh_128k/512k/Plus


Recreation, Brute Forced and Dump of all seven PALs found on the Macintosh Plus. 
5 of the 7 (ASG, BMU1, BMU2, CAS, TSG) were reverse engineered by Porchy of PLD Archive:
https://wiki.pldarchive.co.uk/

The TSM was a converted dump from the Prototype 512K (converted to a GAL, added for completion).

The LAG was independently cracked by Bolle, as well as painstakingly reverse engineered by Alex:
https://github.com/alexthecat123

Both the Bolle LAG and Alex's LAG are present, the other LAG from the Macintosh 512 also works in a plus (and it's assumed the 128k will also work).

Confusion around the CAS - it seems there are two main variants of the Plus CAS here. 
The original CAS from the PLD Archive seems to have an unknown issue, where only one RAM bank works.
(Marked as Broken?)
The second CAS is an older version, which appears to work, with 1mb sticks in all four slots - resulting in 4mb total RAM. Both versions are present, but the "working?" variant is known to work better.

Devices (note, all devices are GALs):
BMU1 - 16V8
BMU2 - 16V8
CAS - 20V8/22V10
TSM - 16V8
TSG - 16V8
ASG - 16V8
LAG - 16V8
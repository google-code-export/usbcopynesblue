Host program to control the USB Copy NES for Windows. Blue version forked from the USB

CopyNES 4.0.0 source available at retrousb.com by rainwarrior.

Current version: 5.0.4 - 5/22/2014
  * Binary: [usbcopynesblue504.zip](https://docs.google.com/uc?export=download&id=0BzdipTil_z3AS0Q1SF9qNzdnTnM)
  * Source: [usbcopynesblue504src.zip](https://docs.google.com/uc?export=download&id=0BzdipTil_z3AbkJ2TGV0UVY0azA)


  * Parallel port connection added.  (currently untested.)
  * NSFs can be loaded onto Glider cart. (back it up first. :) )
  * MAPPERS.DAT format slightly changed. Now easier to add mappers to it.
  * All plugin data, including the ram cart plugins now live in MAPPERS.DAT.
  * Removed a redundant log player that was less capable than the one that was added a while back.
  * NSF log file selection now doesn't include All files (**.**) by default.
  * NSF log player progress bar now shows progress of current song, for logs that happen to contain multiple songs recorded.
  * Corrected the mapper number that is given to NES-EVENT related dumps. (MAPPERS.DAT had it at 132 right from day 1. It should have been 105.)



5.0.3 - 4/29/2014
  * Fixed bugs with the glider flasher.
  * Added a plugin to dump RET-CUFROM boards, (Glider, mapper 29)

5.0.2 - 4/28/2014
  * Lots of bug fixes
  * Added NES 2.0 support
  * Updated u5rom.bin (oversized uxrom dumper, to handle self-flashable uxrom boards between 128-512K (Mapper 30))
  * Added UNROM-512 flasher under RAM-Cart.
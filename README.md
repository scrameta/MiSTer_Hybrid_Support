# MiSTer_Hybrid_Support

Releases/scripts for hybrid emulation of Minimig. i.e. using the arm for 68k emulation and fpga for hardware.

If using qemu for emulation you need to put these in your startup sequence:
games/Amiga/shared/Alloc32P/AllocP
games/Amiga/shared/StackAttack_020
These make the code and data less likely to share a page, which kills qemu performance


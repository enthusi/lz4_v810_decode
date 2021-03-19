# lz4_v810_decode
lz4 decoder for v810 CPUs in assembly language
CPU v810 like in the Virtual Boy or NEC PC-FX
r10=source, r11=destination; 124 Bytes
ISAS Assembler Syntax

Code assumes a 2 byte header (little endian size) and then the raw compressed BLOCK
in lz4 format (up to 64 kB).
Compressed for example with 'lz4 -v -f -12 -B4' and header + tail cropped.

Licensed under the 3-Clause BSD License
Copyright 2021, Martin Wendt

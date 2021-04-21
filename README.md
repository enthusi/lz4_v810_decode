# lz4_v810_decode
lz4 decoder for v810 CPUs in assembly language
CPU v810 like in the Virtual Boy or NEC PC-FX
r10=source, r11=destination; 124 Bytes
ISAS Assembler Syntax

Code assumes a 2 byte header (little endian size) and then the raw compressed BLOCK
in lz4 format (up to 64 kB).
Compressed for example with 'lz4 -12 -B4' and header + tail cropped.

Now it is even listed on the official [LZ4 page](http://lz4.github.io/lz4/). ;-)

Licensed under the 3-Clause BSD License
Copyright 2021, Martin Wendt

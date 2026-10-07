# Boulder Dash Disassembly

This repo contains the data files and scripts used to generate my disassembly of the C64 version of the classic game Boulder Dash. The output of the latest incarnation can be found [here](http://www.retrointernals.org/boulder-dash/boulder-dash-disassembly.html). It's generated using a home-made disassembler (written in Python 3) I'm working on called [negentropy](https://github.com/shewitt-au/negentropy). It's also available in PIP.

## Preserved listing

This organisation fork also archives the author's [HTML listing](listing/boulder-dash-disassembly.html) and its four graphics images from [shewitt-au/Retrointernals](https://github.com/shewitt-au/Retrointernals/tree/master/boulder-dash), retrieved on 2026-10-07. The [author's published page](https://www.retrointernals.org/boulder-dash/boulder-dash-disassembly.html) provides the styled, readable version.

This is a research disassembly, not an established complete rebuild. The generator configuration expects a separately supplied `5000-8fff.bin` memory image, which is absent from upstream.

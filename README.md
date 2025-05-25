# kicad-sipeed-tang-core-boards
A kicad part library for Sipeed tang core boards such as Tang  Primer 25k

## Tang Primer 25K core-board
### Documents
Released specifications from SiPEED included.
Added spreadsheet describing each pin, includes trace-length on core board/SoM.

### Symbol
Symbol divided into 6 units

#### Unit A
Power, VCCIO for banks are excluded, are instead moved to units D, E, F.

#### Unit B
Configuration I/O such as JTAG and named pins Ready, Done etc. and pins from the banks that are firmly set to 3.3V power domain.

#### Unit C
MIPI hard-core pins.

#### Unit D
Bank 2/3 with bank VCCIO configuration pin

#### UNIT E
Bank 0/1 with bank VCCIO configuration pin

#### UNIT F
Bank 6/7 with bank VCCIO configuration pin

### Footprint
Available in variant with 2mm holes, and without 2mm holes.


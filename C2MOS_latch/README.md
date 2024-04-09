# C2MOS latch

## Schematic
A Cadence schematic implementation with simulation test results for the schematic.
Symbol instance for the schematic created with consideration for tiling several of these.

## Layout
A Cadence layout for the schematic implementation.
The power and signal lines (VDD and VSS) are routed horizontally using the metal1 (M1) layer, while vertical connections to the next row are made using the metal2 (M2) layer. 
The latch has been designed to fit within a $10 \mu m \times 10 \mu m$ dimension to ensure proper pitch matching. 

(TBD) The layout has been thoroughly checked and verified to be free of any layout-versus-schematic (LVS) and design rule check (DRC) violations.

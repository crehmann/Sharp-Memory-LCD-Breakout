# Breakout Board for Sharp Memory Display (LS011B7DH03)



![](https://raw.githubusercontent.com/crehmann/Sharp-Memory-LCD-Breakout/main/Pictures/SharpMemoryLcdBreakout.png)

## Bill of Material

| Name                | Qty  | Package | Value                                        | Description                                                  |
| ------------------- | ---- | ------- | -------------------------------------------- | ------------------------------------------------------------ |
| FB1, FB2            | 2    | 0805    | 300mΩ DC Resistance, 600Ω impedance @ 100MHz | Ferrite Bead                                                 |
| C1                  | 1    | 0805    | 560pF                                        | Capacitor                                                    |
| C2, C3              | 2    | 0805    | 1uF                                          | Capacitor                                                    |
| R1/R2               | 1    | 0805    | 10kΩ                                         | Use either R1 **or** R2. Use R2 when VCOM toggling via EXTCOMIN pin (EIN) is used. |
| J3                  | 1    | SMD     | FH12-10S-0.5SH                               | FPC connector with 10 pins and 0.5mm pitch                   |
| LS011B7DH03 Display | 1    | -       |                                              | https://aliexpress.com/item/1005001809102193.html            |

See the BOM csv file in the [release zip-file](https://github.com/crehmann/Sharp-Memory-LCD-Breakout/releases) for LCSC part numbers 

**Note:** The current revision v0.3 is not personally tested. v0.2 was using wrong capacitor values but the schematic worked otherwise ([see picture](https://raw.githubusercontent.com/crehmann/Sharp-Memory-LCD-Breakout/main/Pictures/displayOnBreakoutBoard.png)).


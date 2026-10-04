# Spindle

Spindle is a low-cost, custom e-reader made with the RP2350A. It consists of a 2.7 inch e-paper display, which is much better than a typical screen. It also consists of a 128Mbit flash, which is 16MiB, and 5 user buttons. The firmware for Spindle can be found [here](https://github.com/Keyaan-07/spindle-firmware/tree/main). The firmware is custom written in C. The power consumption averages at about 40mA, making it a low-power device.  

See the board on [KiCanvas](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FAhad732%2FSpindle%2Ftree%2Fmain%2FHardware)  


## Features:
- Dual ARM-Cortex M-33 and Hazard3 RISC-V cores
- WiFi Functionality
- 16MiB flash
- 2.7 inch e-paper display
- 100% open-sourced
- USB High Speed compatible
- switching charging
- low-power consumption

# CAD: 
So, the CAD is made in onshape, [link here](https://cad.onshape.com/documents/20ea073a3a4d1e1a3f911dd9/w/66e638eb5b2ab30e1451aaff/e/b663f709698147c3db960dcd). We have tried our best to make it look as clean as possible.  This is what the assembly looks like:  
![cad-3d](/images/cad-3d-side.png)  
![cad-internal](/images/cad-internal.png)  


## Images:  
![3d-render](/images/cad-3d-top.png)
![3d-side](/images/cad-3d-side-nobg.png)  
![pcb 3d](/images/pcb-3d.png)
![pcb 3d](/images/pcb-3d-side.png)
![pcb](/images/pcb.png)  
![sch](/images/Spindle.svg)  

We made this project as a fun way to learn to integrate various components and work together on different parts of the same project!  

# BOM
|Designator                                      |Footprint                                        |Value                      |Quantity            |Price|Link                                                                                 |
|------------------------------------------------|-------------------------------------------------|---------------------------|--------------------|-----|-------------------------------------------------------------------------------------|
|C1, C2                                          |402                                              |15p                        |100                 |0.09 |https://www.lcsc.com/product-detail/C696887.html                                     |
|C10, C11, C12, C4, C6, C7, C8, C9               |402                                              |1u                         |100                 |0.58 |https://www.lcsc.com/product-detail/C46614477.html                                   |
|C13, C14, C15, C16, C17, C18, C19, C20, C21, C24|402                                              |100n                       |100                 |0.16 |https://www.lcsc.com/product-detail/C5137487.html                                    |
|C23, C25, C26, C27, C3, C5                      |402                                              |4.7u                       |20                  |0.42 |https://www.lcsc.com/product-detail/C318563.html                                     |
|D1                                              |402                                              |GREEN                      |100                 |0.61 |https://www.lcsc.com/product-detail/C55072283.html                                   |
|D2                                              |402                                              |RED                        |100                 |0.55 |https://www.lcsc.com/product-detail/C55072282.html                                   |
|D3, D4, D5                                      |D_SOD-123                                        |MBR0530                    |20                  |0.74 |https://www.lcsc.com/product-detail/C5140024.html                                    |
|J1                                              |USB_C_Receptacle_HCTL_HC-TYPE-C-16P-01A          |USB_C_Receptacle_USB2.0_16P|20                  |0.48 |https://www.lcsc.com/product-detail/C42400234.html                                   |
|J2                                              |PinHeader_1x02_P2.54mm_Vertical                  |Conn_01x02_Pin             |DNP                 |DNP  |                                                                                     |
|J3                                              |Hirose_FH12-24S-0.5SH_1x24-1MP_P0.50mm_Horizontal|Conn_01x24_Pin             |10                  |0.67 |https://www.lcsc.com/product-detail/C19273933.html                                   |
|J4                                              |microSD_HC_Molex_104031-0811                     |Micro_SD_Card              |3                   |2.5  |https://www.lcsc.com/product-detail/C585350.html                                     |
|L1                                              |L_Radial_D6.0mm_P4.00mm                          |47u                        |5                   |0.53 |https://www.lcsc.com/product-detail/C72618.html                                      |
|L2                                              |L_Sunlord_SWPA5040S                              |3.3u                       |20                  |0.77 |https://www.lcsc.com/product-detail/C5289414.html                                    |
|Q1                                              |SOT-323_SC-70                                    |Si1308EDL                  |5                   |0.59 |https://www.lcsc.com/product-detail/C4355112.html                                    |
|R1                                              |402                                              |60.4K                      |100                 |0.09 |https://www.lcsc.com/product-detail/C49653007.html                                   |
|R10                                             |402                                              |1M                         |100                 |0.08 |https://www.lcsc.com/product-detail/C49652954.html                                   |
|R11, R12, R13, R14, R15, R16, R17, R2           |402                                              |10K                        |100                 |0.11 |https://www.lcsc.com/product-detail/C49653007.html                                   |
|R18                                             |402                                              |470                        |100                 |0.06 |https://www.lcsc.com/product-detail/C54920802.html                                   |
|R3, R4, R7                                      |402                                              |1.5K                       |100                 |0.06 |https://www.lcsc.com/product-detail/C54920744.html                                   |
|R5, R6                                          |402                                              |5.1K                       |100                 |0.06 |https://www.lcsc.com/product-detail/C54920813.html                                   |
|R8                                              |402                                              |1K                         |100                 |0.07 |https://www.lcsc.com/product-detail/C54920633.html                                   |
|R9                                              |402                                              |2.2                        |100                 |0.07 |https://www.lcsc.com/product-detail/C54920775.html                                   |
|SW1, SW2, SW3, SW4, SW5, SW6                    |SW_SPST_PTS810                                   |SW_Push                    |10                  |3.43 |https://www.lcsc.com/product-detail/C221895.html                                     |
|U1                                              |QFN-60-1EP_7x7mm_P0.4mm_EP3.4x3.4mm              |RP2350A                    |3                   |3.9  |https://www.lcsc.com/product-detail/C42411118.html                                   |
|U2                                              |VQFN-16-1EP_3x3mm_P0.5mm_EP1.6x1.6mm             |BQ24074RGT                 |3                   |7.59 |https://www.lcsc.com/product-detail/C54313.html                                      |
|U3                                              |SOT-23                                           |MCP1700x-330xxTT           |5                   |0.59 |https://www.lcsc.com/product-detail/C41381676.html                                   |
|U4                                              |WSON-8-1EP_6x5mm_P1.27mm_EP3.4x4.3mm             |W25Q128JVP                 |3                   |2.32 |https://www.lcsc.com/product-detail/C2641199.html                                    |
|U5                                              |rpi_rmc20452t                                    |rpi_rmc20452t              |2                   |10.33|https://www.lioncircuits.com/parts/SC1169                                            |
|Y1                                              |Crystal_SMD_3225-4Pin_3.2x2.5mm                  |12mhz                      |10                  |0.55 |https://www.lcsc.com/product-detail/C16197268.html                                   |
|                                                |                                                 |Battery                    |1                   |4.87 |https://robu.in/product/wly103443-1500mah-3-7v-single-cell-rechargeable-lipo-battery/|
|                                                |                                                 |Screen                     |1                   |14.52|https://robu.in/product/2-7-inch-black-white-e-paper-good-display-with-touch-panel/  |
|                                                |                                                 |                           |PCB+Stencil+Shipping|22.35|                                                                                     |
|                                                |                                                 |                           |Parts Shipping      |8.82 |                                                                                     |
|                                                |                                                 |                           |Total               |88.56|                                                                                     |

# OGX360I-2CH Main PCB.
This board was designed using [Autodesk Eagle](https://www.autodesk.com/products/eagle/overview). You can edit the `.brd` and `.sch` with this program.


## Printed Circuit Board
When fabricating your own, you can download the premade gerbers or generate your own. Suggested PCB properties are:  <br>
*2 layers, 35x71mm, 1.6mm thick, HASL, 1oz copper, no castellated holes, any colour you want!*<br>

## Bill of Materials
All the passive components listed (Resistors, capacitors etc) are listed for reference only. Any equivalents you find would be suitable. Use your best judgement. 
You should check this list against the schematic to ensure nothing is missed.  
**Digikey Quick Cart: http://www.digikey.com/short/zwrw47**  

| Qty | Value/Model | Description | Marking | URL (Passive components provided as sample only) |
| --- | --- | --- | --- | --- |
| 2 | B12B-PHDSS(LF)(SN) | CONN HEADER VERT 12POS 2MM | J4,J5 | https://www.digikey.com/product-detail/en/jst-sales-america-inc/B12B-PHDSS-LF-SN/455-1763-ND/926669 |
| 1 | ‎B6B-PH-K-S(LF)(SN) | CONN HEADER VERT 6POS 2MM | J6 | https://www.digikey.com/product-detail/en/jst-sales-america-inc/B6B-PH-K-S-LF-SN/455-1708-ND/926615 |
| 1 | MIC5219-3.3YM5-TR | IC REG LINEAR 3.3V 500MA SOT23-5‎ | U3 | https://www.digikey.com/product-detail/en/microchip-technology/MIC5219-3.3YM5-TR/576-1281-1-ND/771902 |
| 9 | 08056D104KAT2A | CAP CER 0.1UF 6.3V X5R 0805 | C1,4-5,7-8,10-11,15-16 | https://www.digikey.com/product-detail/en/avx-corporation/08056D104KAT2A/478-08056D104KAT2ACT-ND/11569296 |
| 2 | CC0805JRNPO9BN180 | CAP CER 18PF 50V C0G/NPO 0805 | C2-3 | https://www.digikey.com/product-detail/en/yageo/CC0805JRNPO9BN180/311-1102-1-ND/303012 |
| 1 | EDK106M035A9BAA | CAP ALUM 10UF 20% 35V SMD | C6 | https://www.digikey.com/product-detail/en/kemet/EDK106M035A9BAA/399-14794-1-ND/7319832 |
| 2 | C0805C105Z4VACTU | CAP CER 1UF 16V Y5V 0805 | C9, C14 | https://www.digikey.com/product-detail/en/kemet/C0805C105Z4VACTU/399-8011-1-ND/3471734 |
| 4 | C0805C220J5GACTU | CAP CER 22PF 50V C0G/NP0 0805 | C12-13,17-18 | https://www.digikey.com/product-detail/en/kemet/C0805C220J5GACTU/399-1113-1-ND/411388 |
| 2 | 10118192-0001LF | CONN RCPT USB2.0 MICRO B SMD R/A | J2-3 | https://www.digikey.com/product-detail/en/amphenol-icc-fci/10118192-0001LF/609-4613-1-ND/2785378 |
| 2 | RC0805FR-0733RL | RES SMD 33 OHM 1% 1/8W 0805 | R1-2 | https://www.digikey.com/product-detail/en/yageo/RC0805FR-0733RL/311-33.0CRCT-ND/730809 |
| 2 | RC0805FR-072KL | RES SMD 2K OHM 1% 1/8W 0805 | R3-4 | https://www.digikey.com/product-detail/en/yageo/RC0805FR-072KL/311-2.00KCRCT-ND/730611 |
| 1 | RC0805JR-071KL | RES SMD 1K OHM 5% 1/8W 0805 | R5 | https://www.digikey.com/product-detail/en/yageo/RC0805JR-071KL/311-1.0KARCT-ND/731165 |
| 4 | RC0805JR-0722RL | RES SMD 22 OHM 5% 1/8W 0805 | R6-7,9-10 | https://www.digikey.com/product-detail/en/yageo/RC0805JR-0722RL/311-22ARCT-ND/731232 |
| 2 | RC0805FR-0710KL | RES SMD 10K OHM 1% 1/8W 0805 | R8,R11 | https://www.digikey.com/product-detail/en/yageo/RC0805FR-0710KL/311-10.0KCRCT-ND/730482 |
| 1 | TL3305AF160QG | SWITCH TACTILE SPST-NO 50MA 12V | RESET | https://www.digikey.com/product-detail/en/e-switch/TL3305AF160QG/EG5350CT-ND/5816195 |
| 1 | MAX3421EEHJ+T | IC USB PERIPH/HOST CNTRL 32TQFP | U1 | https://www.digikey.com/product-detail/en/maxim-integrated/MAX3421EEHJ-T/MAX3421EEHJ-TCT-ND/4895460 |
| 1 | CD74HC4050M96 | IC BUFFER NON-INVERT 6V 16SOIC | U2 | https://www.digikey.com/product-detail/en/texas-instruments/CD74HC4050M96/296-14529-1-ND/555596 |
| 2 | ATMEGA32U4-AUR | IC MCU 8BIT 32KB FLASH 44TQFP | U4-5 | https://www.digikey.com/product-detail/en/microchip-technology/ATMEGA32U4-AUR/ATMEGA32U4-AURCT-ND/3440960 |
| 2 | TSX-3225 16.0000MF09Z-AC0 | CRYSTAL 16.0000MHZ 9PF SMD | X2-3 | https://www.digikey.com/product-detail/en/epson/TSX-3225-16.0000MF09Z-AC0/SER4069CT-ND/5413938 |
| 1 | FA-238V 12.0000MB-W3 | CRYSTAL 12.0000MHZ 12PF SMD | X1 | https://www.digikey.com/product-detail/en/epson/FA-238V-12.0000MB-W3/SER3683CT-ND/2403456 |
| 2 | PHDR-12VS | CONN HOUSING PHD 12POS 2MM DUAL | --- | https://www.digikey.com/product-detail/en/jst-sales-america-inc/PHDR-12VS/455-1204-ND/608645 |
| 10 | APAPA22K152 | JUMPER SPHD-001T-P0.5 X2 6" | --- | https://www.digikey.com/product-detail/en/jst-sales-america-inc/APAPA22K152/455-3085-ND/6009461 |
| 1 | 0ZCJ0050FF2G | PTC RESET FUSE 8V 500MA 1206 | F1 | https://www.digikey.com/product-detail/en/bel-fuse-inc/0ZCJ0050FF2G/507-1802-1-ND/4156236 |
| 2 | TMUX1237DCKR | PRECISION ANALOG MULTIPLEXER | U6-7 | https://www.digikey.com/product-detail/en/texas-instruments/TMUX1237DCKR/296-TMUX1237DCKRCT-ND/12165699 |
| 1 | SM06B-SRSS-TB(LF)(SN) | CONN HEADER SMD R/A 6POS 1MM | J7 | https://www.digikey.com/product-detail/en/jst-sales-america-inc/SM06B-SRSS-TB-LF-SN/455-1806-1-ND/926877 |


## Assembled Photo
![Top Side Photo](https://github.com/bolwire/OGX360I-2CH/blob/master/Images/ogx360i-2ch-main_top.jpg?raw=true)
![Bottom Side Photo](https://github.com/bolwire/OGX360I-2CH/blob/master/Images/ogx360i-2ch-main_bottom.jpg?raw=true)
By KingLuxor
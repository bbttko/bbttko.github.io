## fpga boards

| fpga              | Board name | company | board image | notes | repos |
|-------------------|------------|:--------:|:------------:|-----|-------|
| [CycloneIV	EP4CE10](https://www.aliexpress.com/item/32812945851.html?spm=a2g0o.order_list.0.0.21ef1802oBoC0a) | "zeowaa" | altera   | ![](./images/ep4ce10_zeowaa.JPG) | LEDs(8), Buttons(2), Reset(1), EPCS16 |
| [CycloneIV EP4CE15](https://github.com/bbttko/CYCLONE_IV_STARTER_KIT) | qmtech Cyclone4 starter kit | altera   | ![](./images/Cyc4StarterKit.jpg "ep4ce15 qmtech cyclone4 starter kit") | GMII ethernet, VGA 565, Winbond 32MB SDRAM, SPI flash 8Mbytes, CP2102 UART, Button(1), Reset(1), 7-Seg (3), Leds(2) |
| [Max10 10M02SCM153](https://github.com/bbttko/STEP-MAX10)| StepFPGA | altera | ![](./images/StepFPGA_Max10.jpg "max10 StepFPGA") | on-board USB blaster, 7-seg (2), RGB Leds(2), LEDs(8), Switches(4), Buttons(4) |
| [Anlogic EG4S20](https://github.com/bbttko/Tang_FPGA_Examples)| sipeed Tang Primer | anlogic | ![](./images/TangPrimer_Anlogic.jpg "Anlogic TangPrimer") | 64Mbit SDRAM (built-in), 8Mbit Flash, on-board JTAG debugger, TF card, Button(1), Reset(1), RGB LED(1), FPC40P ZIF (display), FPC24P ZIP (camera) |
| [Gowin GW1NR-9](https://github.com/sipeed/TangNano-9K-example) | sipeed Tang Nano 9K | gowin | ![](./images/TangNano9K.jpg "Gowin TangNano9K") | 32Mbit SPI Flash, HDMI, SPI ZIF (display), RGB ZIF (display), onboard JTAG, USB-C uart, Button(2), LED(6) | PicoRV - [PicoRV-TangNano9K](https://github.com/bbttko/PicoRV-TangNano9K)<br>using LCD Led - [Tang9k-lcdled](https://github.com/bbttko/Tang9k-lcdled)<br>SDCard - [Tang9k-sdcard-test](https://github.com/bbttko/Tang9k-sdcard-test) |
| [Cyclone10 10CL006](https://github.com/bbttko/QM_Cyclone10_10CL006) | qmtech | altera | ![](./images/Cyclone10_qmtech.jpg "cyclone10 qmtech") | Micron 32MB SDRAM, 8MByte SPI Flash |


![](./ep4ce10_zeowaa.JPG)


## board images

### <u>zeowaa board</u>
<img src="ep4ce10_zeowaa.JPG" width=10%/><br>
 - ep4ce10
 - 8x LEDs
 - 2x buttons, 1x reset button
 - EPCS16


### <u>Cyclone4 starter kit</u>
\<img src="/Cyc4StarterKit.jpg" width=10% alt="ep4ce15 qmtech cyclone4 starter kit"/\><br>
 - ep4ce15
 - ethernet GMII
 - VGA 565
 - Winbond 32MB SDRAM, SPI flash 8MBytes
 - serial port CP2102
 - 1x button, 1x reset
 - 7-segment display (3)
 - 2x LEDs


### <u>Max10 Step10</u><br>
PicoRV - [PicoRV-StepFPGA](https://github.com/bbttko/PicoRV-StepFPGA)<br>
<img src="https://bbttko.github.io/StepFPGA_Max10.jpg" width=10% alt="max10 StepFPGA"/><br>
 - Max10 10M08SAM
 - on board USB blaster
 - 7-segment (2x)
 - 2x RGB leds / 8x LEDs
 - 4x switches / 4x buttons<br>


### <u>Anlogic TangPrimer</u><br>
<img src="https://bbttko.github.io/TangPrimer_Anlogic.jpg" width=10% alt="Anlogic TangPrimer"/><br>
 - Anlgic EG4S20 (SDRAM 64Mbit built-in)
 - on board JTAG, download debugger
 - TF card socket
 - 1x button, 1x reset, 1x RGB LED
 - Flash 8Mbit
 - FPC40P ZIF socket (display)
 - FPC24P ZIF socket (camera)


### <u>Gowin TangNano9k</u><br>
PicoRV - [PicoRV-TangNano9K](https://github.com/bbttko/PicoRV-TangNano9K)<br>
using LCD Led - [Tang9k-lcdled](https://github.com/bbttko/Tang9k-lcdled)<br>
SDCard - [Tang9k-sdcard-test](https://github.com/bbttko/Tang9k-sdcard-test)<br>
<img src="https://bbttko.github.io/TangNano9K.jpg" width=10% alt="Gowin TangNano9K"/><br>
 - Gowin GW1NR-9
 - 32Mbit SPI flash
 - HDMI connector
 - SPI LCD ZIF (display)
 - RGB LCD ZIF (display)
 - onboard JTAG, USB-C, & usb-uart
 - 2x button, 6x LEDs<br>


### <u>Cyclone10 QMTech</u><br>	
<img src="https://bbttko.github.io/Cyclone10_qmtech.jpg" width=10% alt="cyclone10 qmtech"/><br>
 - Cyclone10 10CL006
 - SPI flash 8MBytes
 - Micron 32MB SDRAM
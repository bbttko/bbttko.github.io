[//]: <> (reference https://www.markdownguide.org/basic-syntax/, https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## boards

| fpga              | board name | company | board image | notes | repos |
|-------------------|------------|:--------:|:------------:|-----|-------|
| [CycloneIV EP4CE10][EP4CE10_site] | _zeowaa_                    | ![](./images/altera.jpg)   | ![][img1] | <sub><sup>LEDs(8)<br>Buttons(2)<br>Reset(1)<br>EPCS16</sup></sub> |
| [CycloneIV EP4CE15][EP4CE15_site] | QMtech Cyclone4 starter kit | ![](./images/altera.jpg)   | ![][img2] | <sub><sup>GMII ethernet<br>VGA 565<br>Winbond 32MB SDRAM<br>SPI flash 8Mbytes<br>CP2102 UART<br>Button(1)<br>Reset(1)<br>7-Seg (3)<br>Leds(2)</sup></sub> | ⛔[PicoRV + Qsys](https://github.com/bbttko/PicoRV-Cyclone4-Qsys)
| [Max10 10M02SCM153][MAX10_site]   | StepFPGA                    | ![](./images/altera.jpg)   | ![][img3] | <sub><sup>on-board USB blaster<br>7-seg (2)<br>RGB Leds(2)<br>LEDs(8)<br>Switches(4)<br>Buttons(4)</sup></sub> |
| [Anlogic EG4S20][Anlogic_site]    | sipeed Tang Primer          | ![](./images/anlogic2.jpg) | ![][img4] | <sub><sup>64Mbit SDRAM (built-in)<br>8Mbit Flash<br>on-board JTAG debugger<br>TF card<br>Button(1)<br>Reset(1)<br>RGB LED(1)<br>FPC40P ZIF (display)<br>FPC24P ZIP (camera)</sup></sub> |
| [Gowin GW1NR-9][TangNano_site]    | sipeed Tang Nano 9K         | ![](./images/gowin.jpg)    | ![][img5] | <sub><sup>32Mbit SPI Flash<br>HDMI<br>SPI ZIF (display)<br>RGB ZIF (display)<br>onboard JTAG<br>USB-C uart<br>Button(2)<br>LED(6)</sup></sub> | [* PicoRV](https://github.com/bbttko/PicoRV-TangNano9K)<br>[* lcdled](https://github.com/bbttko/Tang9k-lcdled)<br>[* sdcard](https://github.com/bbttko/Tang9k-sdcard-test) |
| [Cyclone10 10CL006][CYC10_site]   | qmtech                      | ![](./images/altera.jpg)   | ![][img6] | <sub><sup>Micron 32MB SDRAM<br>8MByte SPI Flash</sup></sub> |

[EP4CE10_site]: https://www.aliexpress.com/item/32812945851.html?spm=a2g0o.order_list.0.0.21ef1802oBoC0a
[EP4CE15_site]: https://github.com/bbttko/CYCLONE_IV_STARTER_KIT
[MAX10_site]:   https://github.com/bbttko/STEP-MAX10
[Anlogic_site]: https://github.com/bbttko/Tang_FPGA_Examples
[TangNano_site]:https://github.com/sipeed/TangNano-9K-example
[CYC10_site]:   https://github.com/bbttko/QM_Cyclone10_10CL006
[img1]: ./images/ep4ce10_zeowaa.JPG
[img2]: ./images/Cyc4StarterKit.jpg
[img3]: ./images/StepFPGA_Max10.jpg
[img4]: ./images/TangPrimer_Anlogic.jpg
[img5]: ./images/TangNano9K.jpg
[img6]: ./images/Cyclone10_qmtech.jpg

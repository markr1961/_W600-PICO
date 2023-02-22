## documentation for W600-PICO

### Summary
- Arm Cortex M3 running at 80 MHz with 1 MB Flash and 288KB RAM.
- Supports hardware cryptography and 2.4 GHz Wi-Fi.

### Specification
- SoC – Winner Micro W600 Arm Cortex-M3 MCU @ 80MHz with 1MB Flash, ??? KB RAM
- Wireless Connectivity – 2.4GHz 802.11 b/g/n WiFi 4 up to 150 Mbps
- USB – 1x Micro USB port for power and programming (via CH340 USB to TTL chip)
- 3.3V I/O Expansion – 2x 10-pin headers with
  - 15x GPIO,
  - 9x PWM,
  - 1x I2C,
  - 1x SPI,
  - 1x UART,
  - Wake Up,
  - Reset.
- Misc – Reset button
- Power Supply – 5V via micro USB port
- Dimensions – 33×20.3mm

### documentation
- [W600-PICO documentation at Wemos.cc](https://www.wemos.cc/en/latest/w600/w600_pico.html)
- [Get started with MicroPython [W600 series] at wemos.cc](https://www.wemos.cc/en/latest/tutorials/w600/get_started_with_micropython_w600.html)

### reviews
- [Microcontroller Monday - Wemos W600 Pico](https://bigl.es/microcontroller-monday-wemos-w600-pico/) 30 January 2020
- read: [$2 Wemos W600-PICO WiFi IoT Board Ships with MicroPython Firmware](https://www.cnx-software.com/2020/01/11/2-wemos-w600-pico-wifi-iot-board-ships-with-micropython-firmware) 11 January 11, 2020
- [A W600-Based Board Running MicroPython for Only $2?](https://www.hackster.io/news/a-w600-based-board-running-micropython-for-only-2-bf4b3561f2ee)
- [A First Look at the Winner Micro W600](https://www.sigmdel.ca/michel/ha/w600/first_look_w600_en.html)  2022-12-15 Includes info on how to update the micro-python that ships with the board.

### micro-Python forums
https://forum.micropython.org/viewtopic.php?t=7652

### [W600-PICO V1.0.0 - wifi board based W600 1MB FLASH MicroPython](https://opencircuit.shop/product/w600-pico-v1.0.0-wifi-board-based-w600-1mb)
W600 – PICO is currently the most recent board released by Wemos. The company is responsible for boards like the D1 and D32. This board is based on a Winner Micro – W600 SoC. The first time users had the opportunity to work with the chip when Seeed released multiple boards starting from late 2018. None of these boards allowed users to utilize the features the chip had to offer ultimately.

The W600 is an Arm Cortex M3 with a clock speed of 80 MHz and 1 MB of Flash. The chip supports hardware cryptography and a 2.4 GHz Wi-Fi. Initially, the W600 has been hinted to take over the ESP8266, but it was never really adopted by the maker community, just like other similar boards. It stayed as a Wi-Fi-to-Serial bridge and had features that already existed in the ESP8226. Nevertheless, the W600 board is still appealing to some users because it houses an ARM core, unlike the ESP8226, which is based on the Xtensa cortex giving it some advantages when used in specific ways.

However, the new board is now changing things as it comes pre-loaded with the Micropython firmware on board. There is a micro USB port available as a source of power and for loading programs. It is connected using a CH340 USB – TTL chip. On both sides of the board, there are 10 pin headers. Some of these are the Wakeup, reset, +5V, and GND pins.

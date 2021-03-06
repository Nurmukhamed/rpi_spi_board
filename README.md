# Orange pi spi board
KiCAD project with SPI NOR flash module (W25QXX DataFlash Board) for orange pi/raspberry pi

This board allow you to boot Orange PI directly from SPI Nor flash without SD card.

  for reference (http://linux-sunxi.org/Bootable_SPI_flash)


sunxi-fel output from orange pi pc and this board with 25q16 spi chip:
```
$ ./sunxi-fel spiflash-info
Manufacturer: Unknown (C8h), model: 40h, size: 2097152 bytes.
```



Components:
```
SPI flash SOIC-8 25 series (for examble 25q08 and above)
PLD-6 (DS1021-2x3S) 2.54mm (for jumper selector)
PBD-8 (DS1023 2x4) 2.54mm (for orange pi connector)
0805 resistor 10Ohm (for led)
0805 led 
```

connect board to red pins (pins 17-24 onboard SPI0)
![pinout](https://github.com/ktkd/rpi_spi_board/raw/master/orangepi-pinout.png)


![pinout](https://github.com/ktkd/rpi_spi_board/raw/master/kicad_spi_nor_opi.png)

![pinout](https://github.com/ktkd/rpi_spi_board/raw/master/photo_boards.jpg)

![pinout](https://github.com/ktkd/rpi_spi_board/raw/master/final.jpg)


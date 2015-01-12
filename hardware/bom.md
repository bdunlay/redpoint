# redpoint prototype BOM

bill of materials for redpoint

### Processor

[CC2540 or CC2541 MCU](http://www.ti.com/lit/ug/swru191f/swru191f.pdf) comes with USB or I2C. The latter is also 30% more power efficient when transmitting, 10% when receiving, and cheaper. SPI or I2C can be used with [ADXL345 accelerometer](https://www.sparkfun.com/products/9836)

* 8051 core
* 128/256 KB flash
* bluetooth LE
* spi
* 4 timers
* 12 bit ADC (8 channels)
* DMA
* usb (CC2540 only)
* I2C (CC2541 only)

### Sensors

subject to change, but good starting points

* [accelerometer](https://www.sparkfun.com/products/9836)
* [altimeter](https://www.sparkfun.com/products/11084)

### I/O

* Bluetooth LE (254X SoC)
* SPI/I2C (sensors)
* LED (for visual status indicator)
* Piezo (for audible status indicator)
* Button (to force start/stop of session)
 
### Memory

* serial flash (data logging)

### Power

* micro usb connector
* [charging circuit](https://www.sparkfun.com/products/10217)
* [battery](https://www.sparkfun.com/products/339)

### Components

* tbd
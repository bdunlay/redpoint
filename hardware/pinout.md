# redpoint prototype pinout

| Pin | Function | Peripheral               |
|:----|:---------|:-------------------------|
| 1   | GND      | Grounded Power Rail      |
| 2   | I2C SCL  | Accelerometer, Altimeter |
| 3   | I2C SDA  | Accelerometer, Altimeter |
| 9   | GPIO     | LED                      |
| 10  | VDD      | Positive Power Rail      |
| 12  | ADC      | Battery Voltage Monitor  |
| 14  | SPI C    | Flash Memory             |
| 15  | SPI SS   | Flash Memory             |
| 16  | SPI MO   | Flash Memory             |
| 17  | SPI MI   | Flash Memory             |
| 20  | GPIO     | Button (Reset)           |
| 22  | XOSC_Q1  | External Clock           |
| 34  | DC       | Debug Interface          |
| 35  | DD       | Debug Interface          |
| 37  | GPIO     | Button (Select)          |

(may add headers + jumpers or dip switch on unused GPIOs)
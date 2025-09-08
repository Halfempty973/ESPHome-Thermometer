# GPIO Overview

Connected to SPI Bus 2 are: SSD1322

spi:
  - id: spi1
    clk_pin: GPIO12
    mosi_pin: GPIO11
    miso_pin: GPIO13
    interface: spi2

Chip Selects SPI2:
SSD1322: GPIO8

Display: 
    spi_id: spi1
    clk_pin: GPIO12
    mosi_pin: GPIO11
    miso_pin: GPIO13
    cs_pin: GPI16
    dc_pin: GPIO1
    reset_pin: GPIO15

ADC-Battery Voltage: GPIO2
ADC NTC1: GPIO5
ADC NTC2: GPIO6
ADC NTC3: GPIO7
ADC NTC4: GPIO8
ADC NTC5: GPIO9

GPIO for Sensor Switch: GPIO10
GPIO for Temperature Switch: GPIO39


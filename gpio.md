# GPIO Overview

Connected to SPI Bus 2 are:
MAX31856 + MAX31856_2 + SSD1322

spi:
  - id: spi1
    clk_pin: GPIO12
    mosi_pin: GPIO11
    miso_pin: GPIO13
    interface: spi2

Chip Selects SPI2:
MAX31856: GPIO2
MAX31856_2: GPIO16
SSD1322: GPIO8

spi2: 
  - id: spi2
    clk_pin: GPIO36
    mosi_pin: GPIO35
    miso_pin: GPIO37
    interface: spi3

Chip Selects SPI3
MAX31856_3: GPIO17
MAX31856_4: GPIO6
MAX31856_5: GPIO18

Display: 
    spi_id: spi1
    clk_pin: GPIO12
    mosi_pin: GPIO11
    miso_pin: GPIO13
    cs_pin: GPIO8
    dc_pin: GPIO1
    reset_pin: GPIO45

MAX31856: 
    spi_id: spi1
    clk_pin: GPIO12
    mosi_pin: GPIO11
    miso_pin: GPIO13
    cs_pin: GPIO2


MAX31856_2: 
    spi_id: spi1
    clk_pin: GPIO12
    mosi_pin: GPIO11
    miso_pin: GPIO13
    cs_pin: GPIO16

MAX31856_3
  - id: spi2
    clk_pin: GPIO36
    mosi_pin: GPIO35
    miso_pin: GPIO37
    cs_pin: GPIO17

MAX31856_4
  - id: spi2
    clk_pin: GPIO36
    mosi_pin: GPIO35
    miso_pin: GPIO37
    cs_pin: GPIO6

MAX31856_5
  - id: spi2
    clk_pin: GPIO36
    mosi_pin: GPIO35
    miso_pin: GPIO37
    cs_pin: GPIO18


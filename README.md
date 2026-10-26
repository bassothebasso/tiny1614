ATtiny1614 Breadboard friendly breakout board design. Not manufactured or tested (yet!)  

# Some features:  
- Attiny1614 (20MHz, 16KB Flash) microcontroller  
- USB-C Power supply w/ AP2112K LDO  
- UPDI Header for programming  
- 600mil DIP form factor  

# Pinout

The board pins are mapped 1:1 to the physical pins of the ATtiny1614 microcontroller

**Left Header**

| J3 Pin | Net / Label | ATtiny1614 Pin | Description |
| :--- | :--- | :--- | :--- |
| **1** | `+3V3` | 1 (VCC) | LDO Out |
| **2** | `PA4` | 2 | GPIO / Alt I2C SDA |
| **3** | `PA5` | 3 | GPIO |
| **4** | `PA6` | 4 | GPIO |
| **5** | `PA7` | 5 | GPIO |
| **6** | `PB3` | 6 | GPIO / Serial RX |
| **7** | `PB2` | 7 | GPIO / Serial TX |

**Right Header**

| J4 Pin | Net / Label | ATtiny1614 Pin | Description |
| :--- | :--- | :--- | :--- |
| **1** | `GND` | 14 (GND) | |
| **2** | `PA3` | 13 | GPIO / SPI SCK |
| **3** | `PA2` | 12 | GPIO / SPI MISO |
| **4** | `PA1` | 11 | GPIO / SPI MOSI / I2C SDA |
| **5** | `UPDI` | 10 (PA0) | UPDI Programming / Reset |
| **6** | `PB0` | 9 | GPIO / I2C SCL |
| **7** | `PB1` | 8 | GPIO / I2C SDA |

**Programming Header**

| J2 Pin | Function |
| :--- | :--- |
| **1** | `UPDI` (Connected to ATtiny Pin 10) |
| **2** | `+3V3` (Target Power) |
| **3** | `GND` (Common Ground) |

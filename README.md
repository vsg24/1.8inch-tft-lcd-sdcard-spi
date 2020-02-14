# Setting up a 1.8 inch TFT LCD with SDCard using SPI to work with Arduino UNO/ESP32

![Alt text](1.8-tft.png?raw=true "ST7735S TFT LCD SPI")

> :warning: Most versions of this display are 5v tolerant, but please check with your supplier before connecting it to 5v!
## 1- Connecting the pins
### For Arduino UNO
| LCD Pin  | Arduino Pin |
| ------------- | ------------- |
| LED  | 3.3v or 5v  |
| SCK (CSK)  | 13 (Hardware SPI)  |
| SDA (MOSI)  | 11 (Hardware SPI)  |
| A0 (DC)  | 9  |
| RESET (RST)  | 8  |
| CS  | 10  |
| GND (MOSI)  | GND  |
| VCC  | 3.3v or 5v  |
### For ESP32
| LCD Pin  | ESP32 Pin |
| ------------- | ------------- |
| LED  | 3.3v or 5v  |
| SCK (CSK)  | 22 (D22) (Hardware SPI)  |
| SDA (MOSI)  | 21 (D21) (Hardware SPI)  |
| A0 (DC)  | 13 (D13)  |
| RESET (RST)  | 14 (D14)  |
| CS  | 12 (D12)  |
| GND (MOSI)  | GND  |
| VCC  | 3.3v or 5v  |

## 2- Write the test code
Replace PIN_NO with the proper pin number from the previous step depending on your board and setup.
> :warning: For Arduino UNO uncomment the
## 3- Connect the board to computer and upload the code!

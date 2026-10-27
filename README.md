# S6TM Detect Carrier 2

Carrier board 2 for the detect series with LTE, TFT display, ToF and environmental sensors

## IC List

- ESP32-S3FH4R2 (Main MCU)
- TPS259472A (5A input efuse)
- 2x TPS6282 (3v3 and 3v8 SMPS)
- SIM7080G (LTE-M/NB-IoT modem)
- W25Q128JVS (16MB program storage spi flash)
- PCF85263A (RTC)
- MS5607 (Pressure sensor)
- HTU21D (Temperature and humidity)
- VL53L0X (ToF ranging sensor)
- SN65HVD230DR (CAN transceiver)
- 5x SN74LV1T125 (SIM level shifters)
- TPD3F303 (SIM ESD protection)
- WS2812B (RGB addressable led)

## Top preview

## Preview 3d render

## Pin definitions

```c
#define I2C_SDA_PIN 16
#define I2C_SCL_PIN 17

#define CAN_TX_PIN 8
#define CAN_RX_PIN 9

#define SPI_MOSI_PIN 5
#define SPI_SCLK_PIN 4
#define TFT_CS_PIN 2
#define TFT_DC_PIN 3
#define TFT_RESET_PIN 6
#define TFT_BL_PIN 7

#define TOF_INT_PIN 18

#define PM_RX_PIN 42
#define PM_TX_PIN 41
#define PM_CS_PIN 38

#define SIM_TX_PIN 35
#define SIM_RX_PIN 34
#define SIM_RTS_PIN 33
#define SIM_CTS_PIN 47
#define SIM_DTR_PIN 48
#define LTE_PWR_PIN 36

#define RGB_PIN 21
#define BTN_PIN 37

#define I_EXT_PIN 1
```

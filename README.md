# S6TM Detect air 1

Air module 1 for the detect series with various co2 and mox air sensors

## IC List

- STM32F103C8T6 (Main MCU)
- HT7533 (MCU 3v3 LDO)
- HTU21D (Temperature and humidity)
- MiCS-5524 (MOX air sensor)
- S88 (CO2 NDIR sensor)
- ENS160 (MOX Sensor)
- SGP41 (MOX Sensors)
- SCD41 ("NDIR" co2 sensor)
- LMC6482 (op amp)
- SN65HVD230DR (CAN transceiver)
- LM73100 (+5V input protection)

## Top preview

## Preview 3d render

## Pin definitions

```c
#define I2C_SCL_PIN PB6
#define I2C_SDA_PIN PB7

#define RS1_PIN PA5
#define RS2_PIN PA6

#define CAN_RX_PIN PB8
#define CAN_RX_PIN  PB9

#define S88_TX_PIN PA10
#define S88_RX_PIN PA9

#define ENS160_INT_PIN PA15
```

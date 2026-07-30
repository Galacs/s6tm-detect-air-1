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

<img width="924" height="905" alt="image" src="https://github.com/user-attachments/assets/d5697c41-7fb4-4b56-806c-0fa1a4baf1ca" />

## Preview 3d render

<img width="943" height="828" alt="image" src="https://github.com/user-attachments/assets/464f2be3-a884-4f92-830b-e6a6159647cc" />

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

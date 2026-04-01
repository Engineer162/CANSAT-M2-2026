# CANSAT-M2-2026 "Rod From God MK1"

This repository contains all the sources for a highly advanced CANSAT based on an STM32 MCU and featuring a rechargeable lithium polymer battery.

Core hardware fields:

| Component        | Model           | Manufacturer       |
| ---------------- | --------------- | ------------------ |
| STM32 MCU (core) | STM32H7S3L8H6   | STMicroelectronics |
| SDRAM chip       | IS42S16800F-7TL | ISSI               |

Power system:

| Component          | Model                   | Manufacturer       |
| ------------------ | ----------------------- | ------------------ |
| STM32 MCU (power)  | STM32L031G6U6           | STMicroelectronics |
| USB-C Connector    | 12402012E212A           | Amphenol           |
| Battery Management | BQ25895RTWT             | Texas Instruments  |
| PD Negotiation     | TPS25730DREFR           | Texas Instruments  |
| Battery            | 1260110 (10000mAh LiPo) | TBD                |

Additionally, it features numerous different sensors for logging, as listed below:

| Sensor                | Model          | Manufacturer       |
| --------------------- | -------------- | ------------------ |
| IMU                   | ICM-42688-PC   | Tokmas             |
| Barometer             | BMP581         | BOSCH              |
| Magnetometer          | MMC5983MA      | MEMSIC             |
| Temperature (outside) | TMP121AIDBVR   | Texas Instruments  |
| Temperature (inside)  | TMP121AIDBVR   | Texas Instruments  |
| Ground distance (ToF) | VL53L1CXV0FY/1 | STMicroelectronics |

And debugging/programming is done via a TAG-CONNECT TC2050-IDC "Plug-Of-Nails™" connector.

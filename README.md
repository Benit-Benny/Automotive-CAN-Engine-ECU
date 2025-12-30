# Automotive CAN Engine ECU Simulation
##CANoe-based CAN simulation for automotive embedded systems
## Overview
This project demonstrates the design of an automotive Engine ECU
using CAN communication. The system is designed using CANoe
(CAPL + DBC) and mapped to STM32 CAN HAL logic.

## Tools
- CANoe (design & documentation)
- CANdb++ (DBC design)
- STM32CubeIDE (logic mapping)
- GitHub

## CAN Message
- Message: EngineData
- ID: 0x100
- Signals: RPM, Speed, EngineTemp
- Period: 100 ms

## CAPL Logic
The Engine ECU periodically updates RPM, Speed, and Temperature
and transmits them on the CAN bus.

## STM32 Mapping
The CAPL logic is mapped to STM32 HAL CAN transmission code,
showing how the same message would be sent on real hardware.

## Note
Simulation execution is not shown due to CANoe license limitations.
The focus is on architecture, message design, and embedded logic.

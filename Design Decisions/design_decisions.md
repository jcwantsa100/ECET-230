# Design Decisions

This document outlines the design decisions made for the ECET-230 project. Decisions are based on system requirements, simplicity, reliability, and feasibility using breadboard-level components.

## System Overview
The project is divided into subsystems based on the block diagram. These subsystems include user inputs, processing, outputs, and power delivery.

## Inputs
Momentary push buttons are used as user inputs. This choice was made due to their simplicity, low cost, and ease of interfacing with a microcontroller. Internal pull-up or pull-down resistors will be used to ensure stable logic levels.

## Microcontroller
A microcontroller is used as the main control unit. It is responsible for reading user inputs, executing program logic, storing data as needed, and controlling outputs. A microcontroller was chosen because it integrates processing, memory, and I/O in a single device.

## Outputs
LEDs are used to provide visual feedback to the user, while a buzzer provides audible alerts. LEDs were selected for their low power consumption and clear indication states. The buzzer allows alerts without requiring visual attention.

## Power
The system will be powered using a low-voltage DC supply suitable for breadboard prototyping. Voltage regulation is handled onboard or through the microcontroller module.

## Block Diagram
The block diagram illustrates the interaction between inputs, the microcontroller, outputs, and power. This diagram serves as the reference architecture for implementation and testing.


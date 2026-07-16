# Multitask-dashboard-using-FreeRTOS-and-STM32
A real-time multitasking dashboard developed on the STM32 NUCLEO-F446RE using FreeRTOS. The system concurrently reads DHT22 temperature and humidity data, transmits it to a PC via UART, and executes LED and counter tasks. Demonstrates RTOS scheduling, STM32 HAL, Embedded C, task management, and real-time embedded system design.


Overview

The Multitask Dashboard using FreeRTOS is an embedded systems project developed on the STM32 NUCLEO-F446RE microcontroller to demonstrate real-time multitasking using FreeRTOS. The application executes multiple tasks concurrently, including DHT22 sensor acquisition, UART communication, LED status indication, and system counter management.

Temperature and humidity data are acquired from the DHT22 sensor and transmitted to a PC through UART, where they are monitored using PuTTY. Each functionality is implemented as an independent FreeRTOS task, demonstrating priority-based task scheduling, modular firmware design, and efficient CPU resource management.

The project follows a layered software architecture using the STM32 HAL, making it scalable, maintainable, and suitable for learning real-time operating system concepts used in embedded applications.

Key Features
Real-time multitasking using FreeRTOS
Independent tasks for DHT22 sensor reading, UART communication, LED indication, and system counter management
Temperature and humidity monitoring using the DHT22 sensor
UART communication for real-time serial monitoring using PuTTY
Priority-based task scheduling with FreeRTOS
Modular firmware developed using Embedded C and STM32 HAL
Efficient task management and real-time execution
Scalable architecture suitable for embedded and IoT applications
Hardware Used
STM32 NUCLEO-F446RE
DHT22 Temperature & Humidity Sensor
USB-UART (Virtual COM Port)
On-board LED
Software & Tools
STM32CubeIDE
STM32CubeMX
FreeRTOS
STM32 HAL Library
Embedded C
PuTTY
Learning Outcomes
FreeRTOS task creation and scheduling
Real-time multitasking concepts
Peripheral interfacing (GPIO and UART)
DHT22 sensor integration
UART-based serial communication
Embedded firmware development using STM32 HAL
Modular software architecture
Debugging and validation of real-time embedded applications

# Multitask-dashboard-using-FreeRTOS-and-STM32
A real-time multitasking dashboard developed on the STM32 NUCLEO-F446RE using FreeRTOS. The system concurrently reads DHT22 temperature and humidity data, transmits it to a PC via UART, and executes LED and counter tasks. Demonstrates RTOS scheduling, STM32 HAL, Embedded C, task management, and real-time embedded system design.


Overview

The Multitask Dashboard using FreeRTOS is an embedded systems project developed on the STM32 NUCLEO-F446RE microcontroller to demonstrate real-time multitasking with FreeRTOS. The application runs multiple tasks simultaneously, including sensor acquisition, LCD updates, UART communication, LED status indication, and system counter management.

Temperature and humidity data are acquired from a DHT22 sensor, displayed on a 16×2 I2C LCD, and transmitted to a PC via UART for serial monitoring. Each functionality is implemented as an independent FreeRTOS task, showcasing task scheduling, modular firmware design, and efficient CPU resource management.

The project follows a layered software architecture using the STM32 HAL, making it scalable and easy to maintain while demonstrating practical real-time operating system concepts used in industrial embedded applications.

Key Features
Real-time multitasking using FreeRTOS
Independent tasks for sensor reading, LCD display, UART communication, LED indication, and counter management
DHT22 temperature and humidity monitoring
I2C LCD interface for live data display
UART communication for PC monitoring using PuTTY
Priority-based task scheduling
Modular Embedded C firmware using STM32 HAL
Scalable architecture suitable for IoT and embedded applications
Hardware Used
STM32 NUCLEO-F446RE
DHT22 Temperature & Humidity Sensor
16×2 LCD with I2C Interface
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
Inter-task communication concepts
Peripheral interfacing (GPIO, UART, I2C)
Sensor integration
Real-time embedded system development
Modular firmware architecture
Debugging and validation of embedded applications

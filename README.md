# STM32-LED
Bare metal STM32 LED control using memory mapped registers in C.


This project demonstrates how to control GPIO on an STM32 microcontroller by directly accessing memory-mapped registers in C without using HAL libraries.

## Description

The program:

1. Enables the clock for GPIOA.
2. Configures PA5 as an output.
3. Sets PA5 HIGH to turn on the onboard LED.

This project was written to practice low-level embedded programming concepts, including:

- Memory-mapped I/O
- Pointer dereferencing
- Register manipulation with bitwise operations
- GPIO configuration
- STM32 architecture

## Hardware

- STM32 Nucleo board (STM32F4 series)
- Onboard LED connected to PA5

## Future Improvements

- Toggle LED with delays
- Multiple LEDs
- Button input
- Debouncing
- Interrupts
- Timer peripherals

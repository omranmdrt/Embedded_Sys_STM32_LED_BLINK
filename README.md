# Embedded_Sys_STM32_LED_BL-NK

# STM32 LED Blink Project

This is a basic STM32 project to blink an LED connected to **PA5** using the **HAL library** and **STM32CubeIDE**.

## Tools Used
- STM32CubeIDE
- STM32F103C8T6 (Blue Pill)
- HAL Drivers

##  Description
This project toggles the onboard LED on pin **PA5** every 500ms.

##  How it Works
- GPIOA and PA5 configured as output
- Inside the `while(1)` loop:
  - The LED is toggled using `HAL_GPIO_TogglePin`
  - 500ms delay with `HAL_Delay`


## ✅ Result
LED connected to PA5 will blink at 1Hz (0.5s on, 0.5s off)

---

> Created by [Umran](https://github.com/omranmdrt)

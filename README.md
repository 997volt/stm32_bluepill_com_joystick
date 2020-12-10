# stm32_bluepill_com_joystick

Joystick module driver. Reads X and Y axis values by ADC and sends results by Serial Port. Used FreeRTOS for threads.

Created in STM32CubeIDE for STM32 "Blue Pill" HW-267 based on STM32F103CBT6 MCU. 

### To run/modify this project locally:

* clone this repository to your STM32CubeIDE workspace
* in STM32CubeIDE `File > New > STM32 Project From Existing STM32CubeMX Configuration File (.ioc)`
* choose .ioc file from cloned repository
* build and run the project
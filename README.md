# What is it?
"FreeAct" is a minimal real-time embedded framework (RTEF) based on the
FreeRTOS kernel. FreeAct implemetns the Active Object design pattern.
It was originally presented by Miro Samek at the
[Embedded Online Conference 2020](https://www.embeddedonlineconference.com/session/Modern_Embedded_Software_Goes_Beyond_the_RTOS)


---------------------------------------------------------------------
# Directories and Files

```
FreeAct/
+-3rd_party/       - third-party software (needed in the examples)
| +-FreeRTOS/      - stripped down FreeRTOS 10.3.1 distribution
| +-CMSIS/         - ARM CMSIS
| +-efm32pg1b/     - low-level code to support the EFM32PG1B board
| +-ek-tm4c123gxl/ - low-level code to support the EK-TM4C123GX board
|
+-examples/
| +-blinky-efm32/  - Blinky-Button exammple for the EFM32PG1B board
| +-blinky-efm32/  - Blinky-Button exammple for the EK-TM4C123GX board
|
+-inc/             - include directory
| +-FreeAct.h      - FreeAct interface
+-src/             - source directory
| +-FreeAct.c      - FreeAct implementation
```

---------------------------------------------------------------------
# Licensing
FreeAct is licensed under the MIT open source license, which is the same
used in FreeRTOS.


---------------------------------------------------------------------
# Contact Information

[state-machine.com](https://www.state-machine.com)

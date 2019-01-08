# Adafruit_ILI9486_STM32

Modifications to original code:  
- Replace Adafruit_ILI9486_STM32.cpp with version from http://stm32duino.com/download/file.php?id=2930  
- This version incorporates SPI transactions to allow master-multiple slaves configuration.
- Change pin definitions in Adafruit_ILI9486_STM32.h.

Based on Adafruit_ILI9341_STM lib: https://github.com/rogerclarkmelbourne/Arduino_STM32/tree/master/STM32F1/libraries/Adafruit_ILI9341_STM

This lib uses the latest SPI features from my repository: https://github.com/stevstrong/Arduino_STM32/tree/master/STM32F1/libraries/SPI

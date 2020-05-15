# Adafruit_ILI9486_STM32

Modifications to original code:  
- Replace Adafruit_ILI9486_STM32.cpp with version from http://stm32duino.com/download/file.php?id=2930  
- This version incorporates SPI transactions to allow master-multiple slaves configuration.
- Change pin definitions in Adafruit_ILI9486_STM32.h.

Based on Adafruit_ILI9341_STM lib: https://github.com/rogerclarkmelbourne/Arduino_STM32/tree/master/STM32F1/libraries/Adafruit_ILI9341_STM

This lib uses the latest SPI features from my repository: https://github.com/stevstrong/Arduino_STM32/tree/master/STM32F1/libraries/SPI  

#### Update: This driver was developed under Roger Clarke's STM32 core which was the only one available back then. Try this new driver https://github.com/ImpulseAdventure/Waveshare_ILI9486 if you want to port the sketches using the official ST core.

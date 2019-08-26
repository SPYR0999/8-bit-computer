# This is a GitHub page for my 8-bit computer project...
# 
# Rev1 of the schematic is comming soon. Stay tuned!
#
# Please keep in ming that any of the informations below are subject to changes.
# The CPU is planned to be an Atmega16a
# The video chip was plannes to be an Atmega328p, however, it might be replaced by an Atmega8 or similar in order to have more GPIO pins. The initial concept may be used in aditions of transistors to set higher addresses lines low while reading because of the low memory allocated to it.
# The sound chip will either be the video chip outputting a PWM signal or an Attiny85 cummunicating with the video chip through SPI.
# The computer will have 32K SRAM located on a single chip. (chip number coming soon)
#
# Here's the current memory map of the computer:
#   0000-7FFF = Total memory
#   0000-03FD = Video memory
#   03E9 = Sound memory
#   03FF = Last key pressed
#   The memory under 03EA and 03FE may be used to check what were the lasts keys pressed on the keyboard.
# Other functions will be implemented under this section for better understanding the memory map.

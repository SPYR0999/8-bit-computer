# This is a GitHub page for my 8-bit computer project...
# 
# Rev1 of the schematic is comming soon. Stay tuned!
#
# Please keep in ming that any of the informations below are subject to changes.
# -Two separate Atmega16a will be used for the CPU and the video chip.
# -Sound will be obtained with 3 NE555 multi-waveforms generators in adition of transistors an Atmega16a, and an Atmega328p. This whole setup will be on a sound card plugging in the computer via expansion slots.
# -The computer will have 32K SRAM located on a single chip. The chip will be an UM61256FK-15. An additional 32K RAM will be available on an expansion card.
# -A redefined character set will be available but only is a RAM epansion card is present (the RAM expansion might be on the sound card, if so, the sound memory will also be in this area).
#
# Here's the current memory map of the computer:
#   -0000-7FFF = Total memory
#   -???? = Video memory
#   -03E9-03EF = Sound memory
#   -03FF = Last key pressed
#   -The memory under 03F5 and 03FE may be used to check what were the lasts keys pressed on the keyboard.
#   -F807-FFFF = Redefined character set
#
# If you have any suggestions or questions about this project let me know and stick around for updates!

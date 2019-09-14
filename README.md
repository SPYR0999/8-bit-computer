# This is a GitHub page for my 8-bit computer project...
# 
# Rev1 of the schematic is comming soon. Stay tuned!
#
# Please keep in ming that any of the informations below are subject to changes.
# -The CPU is planned to be an Atmega16a
# -The video chip was planned to be an Atmega328p, however, it might be replaced by an Atmega8 or similar in order to have more GPIO pins. The initial concept may be used in aditions of transistors to set higher addresses lines low while reading because of the low memory bloc allocated to it. A redefined character set may only be available if a RAM expansion is present.
# -Sound will be obtained with 3 NE555 multiwaveforms genertors in adition of transistors and an atmega8. This whole setup will be on a sound card plugging in the computer via expansion slots.
# -The computer will have 32K SRAM located on a single chip. The chip will be an UM61256FK-15. An additional 32K RAM might be available on an expansion card.
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

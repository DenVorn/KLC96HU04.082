# prot-inf
Dump of firmware and option-bytes from a STM8L151K4T6 on a KL96HU04A BMS mounted in a KLC96HU04.082 e-bike battery.
The data was empty.

## EXTRA
The small programming header is in the following pinout (from the side of the power-mosfets):
- GND
- 3V
- Reset
- Swim

The USART pin that is located at the outside battery terminal is connected through series of resistors to the PC3 (USART TRANSMIT) on the MCU.

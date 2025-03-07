#  KLC96HU04.082 - 36V 9.0 Ah 324 Wh
Dump of firmware and option-bytes from a STM8L151K4T6 on a KL96HU04A BMS mounted in a KLC96HU04.082 e-bike battery.
The data was empty. Although there is an eeprom present, the contents are provided in the 2DCM.bin file.

## EXTRA
The small programming header is in the following pinout (from the side of the power-mosfets):
- GND
- 3V
- Reset
- Swim

The USART pin that is located at the outside battery terminal is connected through series of resistors to the PC3 (USART TRANSMIT) on the MCU.

### Specific components (front)
- 3x RFS3306 
- 1x 12ah4
- 2x IPD053N08N3
- 2x SHARP PC817
- 1x S-1142A
- 3x UC3843
- 2x fuses (below power mosfets)

### Specific components (back)
- 1x STM8L151K4T6
- 3x S-8204B
- 1x BQ27541
- 1x AT24C128C (2DCM B)

### Cells
- 40x Sanyo UR18650AA

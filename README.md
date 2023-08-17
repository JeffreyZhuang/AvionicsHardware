# AvionicsHardware

Custom ARM-Cortex M4 STM32F446 flight computer for UAVs

Changes I would make on next revision:
- ESD protection of reverse polarity protection mosfet
- More jumpers, for example on the M9N to select active or passive antenna
- Larger inductor pads or different inductor to make it easier to solder
- Larger crystal pads for handsoldering (but idk if handsoldering crystal is possible)
- Add a power pin on SWD interface for STlink level shifter
- 0 ohm resistors in case I want to add series resistors or inductors or filtering capacitors later
- Ground pour on all layers
- Use 5v SMPS instead of 5.1v for consistency
- Use handsoldering version of components
- No SOD-323
- No terminal block
- Expose soldermask under switcher so you can solder with iron
- Thermal reliefs
- Series resistors for short circuit protection especially for the raspberry pi interrupt pin incase raspberry pi low and stm32 high causes short

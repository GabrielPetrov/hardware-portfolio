# Implant-Inspired Wireless Sensor PCB

This was a school PCB project for a small wireless sensor designed to measure impedance and temperature.

The board uses an **nRF52811** microcontroller for BLE communication and an **AD5941** analog front end for impedance measurement. Power is handled by an **LTC3588-1**, with a supercapacitor used for energy storage.

## Main components

- nRF52811 BLE microcontroller
- AD5941 analog front end
- LTC3588-1 energy harvesting IC
- CAP-XX HW203F supercapacitor
- 100 kΩ NTC temperature sensor
- 2.4 GHz antenna and matching components

## Project work

I designed the schematic and worked through the connections between the MCU, analog front end, power circuitry and sensors. I also had to consider the power requirements of the different ICs, component selection, footprints, and the RF section around the BLE antenna.

The project was done in KiCad and was mainly a way to get experience designing a board that combines analog measurement, digital electronics, wireless communication and power management.

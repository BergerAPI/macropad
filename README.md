# Macropad

This project demonstrates how to build a simple macropad powered by a microcontroller using the same chip as the Raspberry Pi Pico (RP2040).
You can use the files here to 3D print, assemble, and program your own version!

The video of the project was recorded using a custom microcontroller, which is not yet publicly available.
However, you can safely use a Raspberry Pi Pico instead — it uses the same RP2040 chip, so all firmware and pinouts should work with minimal or no changes.

## 3D Model Notice

The included 3D model files are provided as-is.
Before printing, you must adjust them to include proper tolerances (fit clearance) for your printer and switches — otherwise, parts may fit too tightly or loosely.

## Requirements

- Microcontroller: Raspberry Pi Pico (or basically any microcontroller)
- Firmware: Included in this repository
- Switches & Keycaps: Any standard mechanical key switches
- 3D Printer: To print the enclosure and plate (or just order the parts like I did)

Optional:

- EEPROM chip — required for advanced features like changing macros on the fly like with QMK

⚠️ Note: The Raspberry Pi Pico does not have built-in EEPROM, so this functionality will be unavailable unless you add one externally.

## Getting Started 🚀

- Print the enclosure and plate (remember to add tolerances).
Assemble the hardware.
- Flash the firmware to your Pico (instructions in /firmware).
- Connect to your computer and enjoy your new macropad!

## Open Licence
Feel free to play with the provided files and change them to your liking - I even encourage it.

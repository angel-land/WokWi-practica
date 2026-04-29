# WokWi-practica

This project simulates an 8-button mini piano in Wokwi using a Raspberry Pi Pico and a buzzer.

## Project description

- Eight pushbuttons are connected to GPIO pins and mapped to notes from C4 to C5.
- Pressing a button plays the corresponding tone through the buzzer.
- The sketch uses `INPUT_PULLUP`, so each button reads `LOW` when pressed.
- If no button is pressed, the buzzer is silenced.

## Files

- `sketch.ino`: Arduino sketch for reading buttons and generating tones.
- `diagram.json`: Wokwi circuit definition for the Pico, buzzer, and buttons.

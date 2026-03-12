# MicroPython Quickstart Guide

MicroPython lets you write real Python code for microcontrollers like the BBC micro:bit. Here’s how to get started!

## 1. What You Need
- BBC micro:bit (or other MicroPython-compatible board)
- USB cable
- Computer with internet access

## 2. Set Up
- Go to [python.microbit.org](https://python.microbit.org/) for the online editor
- Plug in your micro:bit via USB

## 3. Write Your First Program
```python
from microbit import *

while True:
    display.show(Image.HEART)
    sleep(500)
    display.clear()
    sleep(500)
```
- This code flashes a heart on the micro:bit display

## 4. Save & Flash
- Click "Download" in the editor
- Drag the downloaded .hex file onto the micro:bit drive
- The micro:bit will reset and run your code

## 5. Basic Commands
- `display.show(Image.SMILE)` — show an icon
- `sleep(1000)` — pause for 1 second
- `button_a.is_pressed()` — check if button A is pressed
- `pin0.write_digital(1)` — turn on a connected device

## 6. Tips
- Use loops (`while True:`) for continuous actions
- Use `import` to access micro:bit features
- Avoid block code: write Python text only
- Try simple projects: LED patterns, button input, sound, sensors

---
For more help, visit [MicroPython Docs](https://microbit-micropython.readthedocs.io/en/latest/).

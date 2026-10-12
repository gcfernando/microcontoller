# MicroPython LED Blink Example for Raspberry Pi Pico 2 W

A small MicroPython example for learning GPIO output and timing on a Raspberry Pi Pico 2 W. The program toggles the onboard LED once per second using `machine.Pin` and `time.sleep`.

## What is included?

- [LED blink guide](PiPico2W/FirstLed/readme.md): the program, an explanation and run requirements.
- [MicroPython source](PiPico2W/FirstLed/main.py): the complete example.

## Run requirements

Use a board running the matching MicroPython firmware. The `machine` module is supplied by MicroPython; this example is intended to run on the board rather than ordinary desktop Python.

Follow the [official RP2 getting-started guide](https://docs.micropython.org/en/latest/rp2/tutorial/intro.html) for firmware setup, then transfer the example to the board with a compatible MicroPython tool.

The code is an introductory LED example. It does not connect to Wi-Fi or require an external service. Hardware execution was not verified in this documentation update.

---

## Documentation links

[Read all MicroPython & Pico Examples guides online](https://gcfernando.github.io/microcontoller/documentation/) · [Project overview](https://gcfernando.github.io/microcontoller/) · [All developer projects](https://gcfernando.github.io/gcfernando/projects/)

# Blink the Pico 2 W Onboard LED with MicroPython

This example demonstrates two basic MicroPython operations: configuring a GPIO output with `machine.Pin` and delaying execution with `time.sleep`.

## Program

```python
from machine import Pin
from time import sleep

led = Pin("LED", Pin.OUT)

while True:
    led.toggle()
    sleep(1)
```

## How it works

1. `Pin("LED", Pin.OUT)` selects the board's named onboard LED and configures it as an output.
2. `led.toggle()` changes the current LED state.
3. `sleep(1)` waits one second before the next state change.
4. The `while True` loop repeats until execution is stopped.

The LED changes state once per second; a complete on/off cycle takes about two seconds. No network connection is used.

## Run it on the board

Install the matching MicroPython firmware for your Pico 2 W, connect through a compatible editor or MicroPython REPL, and run the [source program](main.py). Saving it as `main.py` on the board lets MicroPython run it at startup.

See the official [MicroPython RP2 quick reference](https://docs.micropython.org/en/latest/rp2/quickref.html) and [firmware setup guide](https://docs.micropython.org/en/latest/rp2/tutorial/intro.html). This repository contains the example; the documentation update did not test a physical board.

---

## Documentation links

[Read all MicroPython & Pico Examples guides online](https://gcfernando.github.io/microcontoller/documentation/) · [Project overview](https://gcfernando.github.io/microcontoller/) · [All developer projects](https://gcfernando.github.io/gcfernando/projects/)

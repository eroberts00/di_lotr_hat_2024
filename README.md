# di_lotr_hat_2024
Hat to wear at destination imagination competitions. Inspired by Gandalf's hat from LotR and the Harry Potter sorting hat.

#  Raspberry Pi Pico Information

## Documentation

### [Getting Started with the Raspberry Pi Pico](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico/2)

Setup for new board:
1. Connect board to host via USB while holding down BOOTSEL button.
2. Install MicroPython through Thonny on host.
![image](https://github.com/user-attachments/assets/0f0003d1-4b9b-48ff-8e39-2c25be100ee9)
3. Connect to Thonny shell.
4. Turn on onboard LED.
```
from machine import Pin
led = Pin(25, Pin.OUT)
led.value(1)
```

### [General Documentation](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html)

Notes:
- Max current pin GPIO pin is 12 mA total for all GPIO pins is 50 mA.


### [Datasheet](https://datasheets.raspberrypi.com/rp2040/rp2040-datasheet.pdf)

## Pinout

![image](https://github.com/user-attachments/assets/704c5886-ae5e-4df9-9cd6-029d7c8e579c)


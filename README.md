# bluetooth-rc-car-arduino
A DIY 2WD robot car built with an Arduino Nano and HC-05. Controlled over Bluetooth using a custom Android app.

# Arduino Bluetooth Rover

This is my first real robotics project. I wanted to see if I could bridge the gap between a mobile app and physical hardware using an Arduino Nano.

### How it works:
Basically, the Arduino listens for serial commands from an HC-05 Bluetooth module. When I press a button on my phone, the Arduino tells the L298N motor driver to spin the wheels in a specific direction.

### The Hardware:
* **Brain:** Arduino Nano
* **Driver:** L298N (The red board with the big heatsink)
* **Comms:** HC-05 Bluetooth Module
* **Power:** 6x AA Batteries

### What I learned:
- How to wire an H-Bridge without blowing anything up.
- Setting up Serial communication at 9600 baud.
- Managing power draw (motors are way more power-hungry than I thought).

### Current Status:
It moves! It's a bit slow right now because of the voltage drop across the motor driver, but the logic is 100% solid. Next step is a Li-ion power upgrade.

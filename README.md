# Turntable on Raspberry Pi

![Turntable](https://github.com/raspberrypisig/TurnTableRpi/raw/master/IMG_20181007_172733.jpg)

## Components
1. Analog Feedback servo https://www.adafruit.com/product/1404  attached to a turntable made from wood parts.
   Inspired by https://www.youtube.com/watch?v=O8kA2KKbXCI
2. Servo attached to PCA9685 PWM driver https://www.adafruit.com/product/815 
3. Using Raspberry Pi 3 with Bluetooth LE running python program.
4. Android app written using App Inventor 2

## Installation on Raspberry Pi
1. Enable i2c using raspi-config
2. run **i2detect -l** and **i2detect -y 1** 
3. Install bleno https://github.com/noble/bleno



# Test Raspberry Pi Pico W (RP2040) Access Point

Why?  Just learning at this point.

## Why the Pico W?

Dual core 133MHz controller with plenty of flash and ram, and an onboard WiFi chip?  For $6 USD? What's not to love?

## What this example does

This is the [standard example Access Point](https://github.com/raspberrypi/pico-examples/tree/master/pico_w/wifi/access_point) except for the following:

* broken out into it's own folder, not built from the example tree
* includes multicore
* the second core just blinks the LED
* added a flash script and Makefile to ease my workflow


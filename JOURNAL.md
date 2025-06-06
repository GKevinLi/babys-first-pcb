---
title: "baby's First PCB"
author: "kevin"
description: "Esp32 dev board / flight controller"
created_at: "2025-05-26"
---

# May 26th: Preliminary Research

I have no idea what I'm doing, so I spent some time trying to figure that out. Decided to use KiCAD as my PCB editing software and looked up some information about how to route a USB-C port to the ESP32 microcontroller.

Spent some time actually learning how KiCAD works. No pictures, as it was mostly setup stuff today.

**Total time spent: 3h**

# May 27th: Schematic Editing

Begun the schematic today! Following the documentation, I connected a USB-C port to the esp32 microcontroller. I'm using the AMS1117 voltage regulator for now, but ive heard it isn't the best choice, so I might swap it out later. I also added data protection for the USB D+ and D- lines. Still have to integrate the gyro as well as buttons for microcontroller reset and stuff.

![image](https://github.com/user-attachments/assets/f27f9fba-0724-4900-86f3-776b7295a620)

**Total time spent: 1h**

# May 29th: Finished schematic version 1

Figured out the gyro I was going to use (MPU6050) and dug through some documentation to figure out how to connect it up. Also added boot and reset buttons as well as mounting holes and GPIO pins to the schematic.

![image](https://github.com/user-attachments/assets/5f51e6bc-17ec-4b16-9ee0-3253c81fec1e)


**Total time spent: 3h**

# Mood Tracker

A compact, handheld mood tracker with a colorful OLED screen, joystick control, microSD logging, LiPo battery power. Designed for portability and with personalization.

Upon powering on, the mood tracker will display a welcome screen with the current time and battery status. There will be a scrollable mood selection menu where you press 'A' to confirm (log is then written in real-time to SD card with date / time + mood. Plug microSD card into a computer to review trend. **UNDECIDED** UPDATE TO SHOW TREND ON SCREEN VIA GRAPH)

## FEATURES
  - Joystick navigation = scroll through the different moods and menus with an analog        stick.
  - RTC = accurate timestamping for logging mood entries
  - OLED Display = displays mood icons and battery level.
  - microSD Logging = stores each mood entry with date, time, and mood
  - 2000mAH LiPo Battery = rechargeable via USB; opted for the 2000mAH vs 500mAH for +20     hours of runtime
  - On / Off Power Switch = clean power cycling
  - Battery Monitoring = real-time voltage level display on screen
  - **UNDECIDED** Speaker = confirmation tone when logging mood

## HARDWARE **UPDATE W/ LINKS**
  - 3D-Printed Case (going for something similar looking to a Gameboy lol)
  - Adafruit Feather M0 Express - I opted for this micrcontroller because it has built-      in LiPo charging. You could use the Arduino Nano as well, but be wary of pin             placement. Sizing is a different so you may need to adjust the 3D model.
  - 0.96" OLED Color TFT Display (w/ microSD slot)
  - DS3231 RTC Module - Real-time clock module for timestamping.
  - Joystick - I used a joystick but you could also use a 5-way navigation switch.
  - 2x Tactile Buttons - For A / B buttons
  - 2000mAH LiPo Battery - Again, I opted for the 2000mAH because of the 20+ hour            runtime and for the sake of compactness, it wasn't that much bigger than the 500mAH.
  - JST On / Off Switch
  - Mini Speaker - **UNDECIDED**
  - 2x 100k OHMs Resistors (only need one resistor if not using the speaker)
  - 1x 1k OHM Resistor



## DATA FORMAT (logged to microSD)
  CSV Format:
2025-06-20, 13:42; Happy :)
2025-06-20, 19:15; Exhausted
etc.



## LICENSE
MIT License. Feel free to build, remix, or improve this project!

## CREDITS
A random impulse and a lot of caffeine.



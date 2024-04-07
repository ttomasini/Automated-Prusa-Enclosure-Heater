# Automated Heating System for the Original Prusa Enclosure

This repo contains the software for the Automated Heating System for the Original Prusa Enclosure, which is designed and published by me (user @lars at printables.com).

Link to the model on Printables: https://www.printables.com/model/561491

This repository contains some bug fixes, new features and is specially optimized for the [Enclosure Heater PCB](https://github.com/ttomasini/automated-enclosure-heater-pcb). Nevertheless the code can (still) be also used with the original setup from Lars. Just make sure that you are using the correct `configuration.h`.

It is designed to run on an Arduino Nano (the original one with an ATMega328p) as well as on Arduino Nano Every (ATMega4809), so it tries to uses little RAM while still being able to drive the 128x64px OLED display, which already eats up half of it.

Enabling serial without reducing the buffer size may result in crashes, as there is not that much RAM free then.

Thanks to @Prusa3D for designing a great enclosure and publishing STEP files of it - this project was only possible because of it.

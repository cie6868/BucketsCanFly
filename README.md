# BucketsCanFly
A Raspberry Pi-powered quadcopter with a camera and a WebSockets-based control interface. GPLv3-licenced.

## Software
* [The Brain](https://github.com/cie6868/BCF_Brain) - Controls the BCF, serves up a web interface and listens to WebSockets.
* [Web UI](https://github.com/cie6868/BCF_WebControlUI) - JavaScript, gamepads and WebSockets to guide the BCF.
* [Firmware for the ESCs](https://github.com/cie6868/Neewer-I2C-bluerobotics-tgy) - SimonK firmware with I2C-based communication for tgy-compatible ESC units.

## Hardware
* Motor Mounts - 3D designs to hold a motor in place.

## History
1. Summer 2013 - RC-plane engines powered by methanol with servos to adjust fuel intake. Controlled by an Arduino. Failed miserably.
2. Summer 2014 - Electric motors with generic ESCs that responded too slow for decent stabilisation. Heavy aluminium frame. Still using an Arduino.
3. Winter 2017 to present - Newly flashed firmware drives ESCs to great response rates. Stabilisation in progress. Switched to a Raspberry Pi with an attached camera. WiFi for transmission. Published on GitHub.

## Credits
A very Sri Lankan project.
* Gamini Obeyesekere
* Chamath Ellawala
* Kavindha Ratwatte
* Vinu Abeygunawardene

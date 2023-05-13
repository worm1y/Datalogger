# Datalogger
An Arduino-based datalogger for multiple thermocouple sensors.

The purpose of this project is to build a cheap and versitile datalogger with multiple sensor inputs (at least 4, but up to a couple dozen in the future).  Most of the sensors will be K-type thermocouples on the final project, intended to take readings of a fire environment in and around a building in a wildfire, or just of multiple places in a forest environment during a fire (controlled or wildfire).

Due to the high tempurature environment, the datalogger itself is intended to be buried in the ground at the test site while the sensor cables will be exposed to the fire environment.  This will require the datalogger to run on battery power as well as being light and compact for ease of transport by foot in backcountry forest.  The code will need to be as efficient as possible to make the most use of the limited battery power while the unit is left in the field for (possibly) weeks.

The Arduino unit is An Arduino Uno R3.
The Datalogger is an Adafruit Data Logger Shield https://learn.adafruit.com/adafruit-data-logger-shield/overview.
The thermocouples are K-Type thermocouples interfacing with MAX6675 Thermocouple Module.

I'd also like to build in a couple on-board LEDs to use as process indicators for field use so users can ensure proper function before leaving the test without having to synch up to the Arduino IDE onsite.

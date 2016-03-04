# ArduinoLoadCell
This Project have with INA125 integrated and arduino


I had a bunch of parts come in this week:

A 85lb. Load Cell (Arduino Scale project)
DHT-11 Temp / Humidity Sensors
Breadboard dual voltage (3.3/5v) power supply
Motion Sensors
3 axis accelerometer

Still in transit:

DHT-22 Temp/Humidity Sensor
Waterproof DS18B20 Temp Sensor

I have my work cut out for me, and updated code and tutorials will be posted. Contact me if you want any of our protoboard projects listed in the various tutorials I post here.

On this load cell (from a Accuteck  W-8260-86W Postal Scale) the 4 wires coming from the load cell are:

Red: Excitation +
White: Signal +
Green: Signal -
Black: Excitation -

This matches the GSE / NCI / Sensotec wiring scheme. To increase the output of the load cell so that the Arduino can read it on an analog input, we will need a INA125P amplifier and a 10 ohm resistor.

* 4/11/13 update: Our free sample INA125P came in today from Texas Instruments. Many electronics manufacturers will send you free samples for prototyping projects. Atmel sent us 3 free 328P-PU processors.

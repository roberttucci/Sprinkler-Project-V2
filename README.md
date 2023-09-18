# Sprinkler-Project-V2
Sprinkler_Project

18 zone sprinkler control with ESPhome and Home Assistant

This project uses an ESP32-Wrover Board that controls 3 banks of relays for Main valves and Zone valves. Included in the project are the ESP32 YAML code, pt. to pt. wiring diagrams, Home Assistant Lovelace YAML, and additions to the HA sensors.yaml, binary_sensor.yaml, and configuration.yaml files

The files will need to be tweaked to support your entity naming and such.

The HA Lovelace code will also need to be edited to match the entity names to match your HA entity assignments.

You will probably need to download the schematic files to your PC to zoom in to read.

Approximate Bill of Materials:

1 ESP32-WROVER

1 Dafurui 10 Pack LM2596 DC-DC Adjustable Buck Converter

2 INA219 DC Current Sensor

2 PCF8575 I/O Expander

1 TCA9548A I2C Mux

2 SSD1306 .96 OLED

1 3.2" SPI ILI9341 Display

1 BME280 sensor

1 ON-OFF Rocker Switch

1 3-01-0371 HiLetgo 12V 4 Channel Relay

3 AEDIKO 8 Channel Relay Module DC 5V Relay Board with OPTO-Isolated Support High or Low Level Trigger

2 12-pin or 3 8-pin through enclosure wall connectors

1 DIY Electronic Project Case Power Enclosure 10.63"x13.39"x3.15" (approx. size)

Brass Standoffs for breadboard

2 6-pin MOLEX connectors (or whatever you want to use) for main valves

2 5-wire 3/4" US Solid SS motorized valves (I used these for the main valves. You do not really need them for the sprinklers to work)

4 12v led indicator lights- 2 red, 2 green

This is an approximate list of the parts you will need, depending on how you mount and wire the components.

I used a YUNGUI 15X18.5 cm Solderable Breadboard, Yohii Pin Header Single Row 2.54mm Pitch 12 Terminals Straight Header Sockets, different size pcb screw connectors, 22 AWG stranded wire for the control wiring, 18AWG solid core for the 24vac sprinkler valve wiring, etc.

All the discrete boards were made pluggable for easy replacement.

I also used board to wire disconnects to detach the cover if I want. but you do not have to.



![image](https://github.com/roberttucci/Sprinkler-Project-V2/assets/88236450/cb6379f6-dcff-4ee2-9a70-21d18ec6385a)




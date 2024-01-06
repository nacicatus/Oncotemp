# Oncotemp

This was commissioned by an Oncology lab to get alerts from their refrigerator. Sort of a primitive IoT project.

This script was originally created by Arnaud Balmelle to connect to Oregon Scientific BLE Weather Station

Copyright (c) 2016 Arnaud Balmelle

This script will connect to Oregon Scientific BLE Weather Station and retrieve the temperature of the base and sensors attached to it.
If no mac-address is passed as argument, it will scan for an Oregon Scientific BLE Weather Station.

Supported Oregon Scientific Weather Station: EMR211 and RAR218HG (and probably BAR218HG)

## Usage: 
python bleWeatherStation.py [mac-address]

## Dependencies:
- Bluetooth 4.1 and bluez installed
- bluepy library (https://github.com/IanHarvey/bluepy)

## License: 
Released under an MIT license: http://opensource.org/licenses/MIT

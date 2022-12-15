fork from @alternate32 to work without TOON.

## esp-lg-control -> Hobby project!
ESP8266 based controller for LG Therma V Monoblock Unit.
Connects the LG to HomeAssistant and tries to optimise output modulation.
Tested with 3-phase 12kW U33 version. So propably works at least with 12-14-16kW U33 3-phase models. May also work with 1-phase and U44 models (depending on modbus registers). But not tested.

This is a hobby project. I share this to allow other people to pick up ideas and contribute. All assistance is welcome. I will not provide support, so use at your own risk. And make sure you know what you are doing, by using this script it is possible that your unit stops functioning or breaks and you could electrocute yourself.

## Hardware
Works with any ESP chip/board supported by ESPHome.

Modbus communication is done through a rs485 to TTL converter based on the max485 chip. I use a board with automatic flow control. You can use other boards if you like. 

## Installation
* Clone repo
* Copy config/config-example.yaml to config/config.yaml
* Update config.yaml
* Update secrets.yaml
* Build

## Disclaimer
This is an experimental script and in early alpha stage. This is in no way finished software and should only be used by professionals. You are using this on your own riks. Do not use if you don't have any soldering/programming experience. Pull request are welcome! 

# homebridge-esphome-ac


[Homebridge](https://homebridge.io) plugin for ESPHome AC Accessories.

## Fixes from original plugin

This forks fixed the issue where the accessory doesn't change to IDLE state if it reaches the target temperature.

This fork enables AUTO mode

This fork fixed to restore the last mode when turning on the AC from the HomeKit tile

## Why this plugin?

I created this plugin because I did not like the Home Assistant integration for Air Conditioner in HomeKit. this plugin give better control over AC accessory with fan speed and oscilate directly from the accessory settings instead of adding another fan accessory.

It also better shows the state of Cooling/Heating and allow to turn ON/OFF by one tap from the home screen instead of going into the accessory settings..

## Installation

You can configure each of the esphome devices directly from the Homebridge UI or view the attached config-sample.json to see how to configure with the config.json file

The plugin will automatically collect your configurations from ESPHome and will allow those to be controlled from HomeKit

* DRY and FAN modes currently not supported.


-------------------------------------------


## ESP32 and ESP8266 currency exchange rates monitor

This is a joke project made by [VolosR](https://github.com/VolosR/currency240240) that loads and displays selected currency rates.

I changed the structure of the project to be run as Platformio project, because
- I want to run is on both esp8266 and esp32
- I want to run it with multiple screen options
 
### Why

I'm working on my own development boards for both listed MCUs and this project is a good demonstration of kind of projects they would happily support

## Configuration

Specify your wifi credentials at the top of [platformio.ini](/platformio.ini) file

### Demo

#### ESP8266

![esp8266](/doc/demo/VID_20211220_235805.gif)

#### ESP32

![esp32](/doc/demo/VID_20211220_220307.gif)

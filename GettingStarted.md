# Getting Started with Thonny MicroPython (Python) IDE for ESP32 and ESP8266


## Installing Thonny IDE
In this guide, we provide instructions to install Thonny IDE in different operating systems, read the section that fits your needs:
- https://randomnerdtutorials.com/getting-started-thonny-micropython-python-ide-esp32-esp8266/#install-thonny-ide-windows

## Flashing MicroPython Software
MicroPython isn’t flashed onto the ESP32 or ESP8266 boards by default. The first thing you need to do to start programming your boards with MicroPython is flash/upload/burn the firmware.

There are different ways in which you can do that. Thonny IDE comes with a tool that allows you to quickly install MicroPython firmware on your board. 

### Flashing MicroPython Firmware using Thonny IDE
In this section, you’ll learn how to flash MicroPython firmware on your boards using Thonny IDE. Follow the next steps:

1) Connect your ESP32 or ESP8266 board to your computer.

2) Open Thonny IDE. Go to Tools > Options > Interpreter.

3) Select the interpreter you want to use accordingly to the board you’re using and select the COM port your board is connected to. Finally, click on the link Install or update firmware.

![screenshot](images/thonny_interpreter.png)

4) Select the port once again, and then click on the Browse button to open the .bin file with the firmware you’ve downloaded on the previous step. Select the options as shown in the picture below and finally click on Install

![screenshot](images/thonny_flash.png)

After a few seconds, the installation should be completed.
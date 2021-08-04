# File-Manager
Install these libraries : GuiSlice, sdFat, adagruit GFX, Adafruit TouchScreen, Adafruit BusIO, MCUFRIEND_kbv

configure GUIslice to use MCUFRIEND_kbv 4 wire display

enable GSLC_SD_EN 1

Hardware SPI is used for SD card

this example is designed to work on a 320x240 display, mcufriend display. If you have a different module or lcd, please choose the correct one in guislice_config.h

Project is structured for platform-io, if you want to use Arduino IDE, then copy all code from main.cpp and make a new project in arduino. Also copy the File_Manager_GSLC.h file and keep it in the same directory of the arduino .ino file.

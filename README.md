DueFlashStorage
===============
DueFlashStorage saves non-volatile data for Arduino Due.
The library is made to be similar to EEPROM library
Uses flash block 1 per default.

Note: uploading new software will erase all flash so data written to flash
using this library will not survive a new software upload. 

Inspiration and some code from Pansenti at https://github.com/Pansenti/DueFlash

Examples
========
DueFlashStorageExample.cpp
/* This example will write 3 bytes to 3 different addresses and print them to the serial monitor.
   Try resetting the Arduino Due or unplug the power to it. The values will stay stored. */
   
DueFlashStorageStructExample.cpp
/* This example will write a struct to memory which is a very convinient way of storing configuration parameters.
 Try resetting the Arduino Due or unplug the power to it. The values will stay stored. */

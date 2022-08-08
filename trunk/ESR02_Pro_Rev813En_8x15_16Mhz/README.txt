make
avrdude -v -p m328p -c arduino -P /dev/ttyUSB0 -U flash:w:mega328_st7565.hex -U eeprom:w:mega328_st7565.eep -B 115200

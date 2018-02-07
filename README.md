# BioVill_Badge
DEFCON Micro Fluidics Badge Design For Biohacking Village

## Features Lifted From OpenDrop
* Arduino Micro
* HV507 64 bit high voltage SIPO
* OLED display 
* Feedback circuit 
* Two pushbutton switches
* Joystick
* Speaker
* Various LEDs
* Various test points
	
	
	
## Power Supply	
Most important change from OpenDrop is the power supply. This board is asking to be plugged into the mains. Super important to isolate the grounds. Pay attention.

### Low voltage power supply sharing ground with USB 

* 5VDC supplied by USB connection to computer or battery on Vin
* 3V3 supplied by the Arduino Micro
		
### High voltage power supply sharing ground with high voltage input

* High voltage in to HV507

### High voltate input specs

* 110VAC <> 240VAC 50Hz <> 60Hz
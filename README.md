# LeonardoISP

The Arduino Leonardo uses a different pinout for ICSP operations than the standard ArduinoISP sketch indicates. This sketch has updated comments and works as follows:  
#  Device being programmed: Leonardo Pin  
slave reset: 10  
MOSI: MOSI  
MISO: MISO  
SCK: SCK  
VCC: 5V or VCC on ICSP header  
GND: Any GND pin or GND on ICSP header  
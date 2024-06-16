The code will work whether your LCD2004A has an 0x27 or 0x3F address

WIRING
LCD gnd > ESP32 gnd (the one next to GPIO23)
LCD vcc > ESP32 5v
LCD sda > GPIO21 
LCD scl > GPIO22

CODING
Open Arduino IDE
Go to tools > Manage libraries
Download the "LiquidCrystal_PCF8574" module
Choose code either with or without module
Paste and upload the code I included in this repositry

Ask ChatGPT to twist the code according to your needs.

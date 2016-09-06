# rpi3-timelapse
This is a modified Timelapse Camera Controller for Raspberry-Pi.
The inspiration of doing this is here https://github.com/dps/rpi-timelapse.

# Code Modification 
The modifications in the code are 
- how the ui.py get access the new GPIO library
- how to initialize Adafruit_CharLCDPlate using new Adafruit_CharLCD library
- how to interact the 1602 LCD with new Adafruit_CharLCD library

# Dependencies Setup
Other RPi dependencies setup 
- setup gphoto2 from source instead of apt-get the binary
- setup ffmpeg from source

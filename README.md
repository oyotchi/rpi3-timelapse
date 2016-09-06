# rpi3-timelapse
This is a modified Timelapse Camera Controller for Raspberry-Pi.
The inspiration of doing this is here https://github.com/dps/rpi-timelapse.

# Code Modification 
The modifications in the code are 
- change how the ui.py get access the new GPIO library
- change how to initialize Adafruit_CharLCDPlate using new Adafruit_CharLCD library
- change how to interact the 1602 LCD plate with new Adafruit_CharLCD library
- change how to interact with Nikon D90 instead of Canon EOS350D
- need to input the maximum frame to shoot after enter shutter speed and ISO 

# Dependencies Setup
Other RPi dependencies setup 
- setup gphoto2 from source instead of apt-get the binary
- setup ffmpeg from source

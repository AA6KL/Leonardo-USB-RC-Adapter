# Updtaed USB RC Joystick Adapter
The original voroshkov/LeoNardo-USB-RC_Adapter(https://github.com/voroshkov/Leonardo-USB-RC-Adapter) is good up to Arduino 16.4.  
For latest version of Arduino, a new Joystick class needs to be created.  Compiled successfully on Arduino 1.8.2.

# USB RC Joystick Adapter
This project turns Arduino Leonardo (or Pro Micro) into a USB adapter for RC transmitter.
The adapter can be used to play [FPV Freerider](http://fpv-freerider.itch.io/fpv-freerider) 
or other flight simulators. 

The project is based on voroshkov/LeoNardo-USB-RC_Adapter(https://github.com/voroshkov/Leonardo-USB-RC-Adapter)

#Flashing:
- Copy the Joystick folder to the Arduino installation folder, under "libries"
- Open the sketch in Arduino IDE, choose Leonardo board, upload.

#Connections:
- RC PPM out <==> Digital Pin 4 of Arduino Leonardo
- RC GND  <==> Arduino GND

#Usage:
In Windows: open *Devices and Printers* find *Arduino Leonardo*. Then right click on it and choose *Game controller settings*. Calibrate joystick using your RC transmitter connected.  Or just search for "USB Game controller".

I will test it with Flysky FS-i6 transmitter, FS-iA6B receiver for FPV FreeRider simulator.

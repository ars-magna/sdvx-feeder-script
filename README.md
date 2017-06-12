# sdvx-feeder-script

Python script for FreePIE to translate keypresses to analogue knobs in vJoy

FreePIE: http://andersmalmgren.github.io/FreePIE/

vJoy: http://vjoystick.sourceforge.net/site/index.php/download-a-install/download

Download SDVX-KB.py and load it into FreePIE (RUN AS ADMIN) with a vJoy controller set up and you're good to go, may have to reboot after installing vJoy, experience may vary. Edit loop delay and math values to your preference. 

MAKE SURE YOU RUN FreePIE AS ADMIN

NOTE: In the event that "vJoy" does not appear in the Device dropdown within config.bat (bemaniPC), simply add a second vJoy device (any tab) to the vJoy Configuration application, then delete the first vJoy device, followed by re-adding your first vJoy device, and finally deleting your second (unnecesary device). This will essentially 'refresh' your first vJoy. The vJoy device should now be selectable inside the config.bat (BemaniPC) application.

Here is how vJoy/BeamaniPC looks configured:

![Settings window](https://dl.dropbox.com/s/ypammrb5a7neqfo/this2.png)

Work in Progress: A tray app to replace FreePIE that just loads the script and a config.. whenever I get around to it. 

Check it out here: https://github.com/ars-magna/sdvx-feeder

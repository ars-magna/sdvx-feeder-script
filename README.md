# sdvx-feeder-script

Python script for FreePIE to translate keypresses to analogue knobs in vJoy

FreePIE: http://andersmalmgren.github.io/FreePIE/

vJoy: http://vjoystick.sourceforge.net/site/index.php/download-a-install/download

Download SDVX-KB.py and load it into FreePIE (RUN AS ADMIN) with a vJoy controller set up and you're good to go, may have to reboot after installing vJoy, experience may vary. Edit loop delay and math values to your preference. 

MAKE SURE YOU RUN FreePIE AS ADMIN

If vJoy isn't working properly, add a second vJoy device (any tab) to the vJoy Configuration application, then delete the first vJoy device, followed by re-adding your first vJoy device, and finally deleting your second (unnecesary device). This will more-or-less 'refresh' your first vJoy. Then edit controller settings in SDVX e-Amuse Cloud as needed.

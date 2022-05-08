# tuya-ha-hacks
Just a clone af the 3v1n0 tuya-hassio hacks, give him credits  
https://github.com/3v1n0/tuya-ha-hacks


Just clone https://github.com/DarkoMir/tuya-ha-hacks in your custom_components folder so that it’s called tuya (to override the default one):

`git clone https://github.com/DarkoMir/tuya-ha-hacks.git tuya`  

And on reboot, the custom component will be used instead of default one.   
Adjust the hardcoded multiplier (TUYA_TEMPERATURE_MULTIPLIER) in case yours doesn’t use values multiplied by 2.

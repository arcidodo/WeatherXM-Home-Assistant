buy an USB RTL-SDR usb dongle.

install both addons from this repo:
https://github.com/pbkhrv/rtl_433-hass-addons/

create an new file in the /config/ directory with the name "rtl_433.conf.template"
copy the content from the file "rtl_433.conf.template" of this repo into that file.
and edit the MQTT settings for your envoirment. 

set the rtl_433 addon config path to "rtl_433.conf.template"

start both addons, if everythins is corect you get the data from the weather station in HA.

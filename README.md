buy an USB RTL-SDR dongle.
i use this one: 

![dongle](https://user-images.githubusercontent.com/678514/204734219-f6bddef1-f429-4a63-9816-fb33c63c3114.jpg)

install both addons from this repo:
https://github.com/pbkhrv/rtl_433-hass-addons/

create an new file in the /config/ directory with the name "rtl_433.conf.template"
copy the content from the file "rtl_433.conf.template" of this repo into that file.
and edit the MQTT settings for your envoirment. 

set the rtl_433 addon config path to "rtl_433.conf.template"

start both addons, if everything is corect you get the data from the weather station in HA.

![Scherm­afbeelding 2022-11-30 om 08 33 25](https://user-images.githubusercontent.com/678514/204734683-ed8e26fd-6fc7-4589-8fad-af3d9087f07f.png)

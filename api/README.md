
add your email and password on line 4 in the configuration.yaml 

    payload: '{"username": "example@wxm.com", "password": "verrystrongpassword"}'



To get your cellid you need to navigate to https://explorer.weatherxm.com click on your device and your cellid is now visable in the URL. (remove the #)
example:

<img width="575" alt="Schermafbeelding_2022-12-01_om_08 03 30" src="https://user-images.githubusercontent.com/678514/205918480-bab2fae7-968a-4b85-8fa3-7e59e0e7878d.png">

Change in the URL the ```CELLID``` to your cellid
https://api.weatherxm.com/api/v1/cells/CELLID/devices

you need the value of the ID field example: f9a601c0-1234-1234-1234-4f669f2d96bd

now you have your ID and your cellid, open the sensors.yaml and edit the flowing lines.

CELLID:
Line 6 add your cellid.

ID:
Line 25, 48, 71, 94, 117, 140 and 152 youre ID

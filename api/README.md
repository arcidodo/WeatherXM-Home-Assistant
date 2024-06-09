
add your email and password on line 4 in the configuration.yaml 

    payload: '{"username": "example@wxm.com", "password": "verrystrongpassword"}'

go to the explorer click on your station HEX and the CELLID is visable in the url

add the cell id in this url: and navigate to is in your browser.
https://api.weatherxm.com/api/v1/cells/CHAMGEME/devices

you need the value of the ID vield example: f9a601c0-1234-1234-1234-4f669f2d96bd

now you have your ID and your cellid, open the sensors.yaml and edit the flowing lines.

CELLID:
Line 6 add your cellid.

ID:
Line 25, 48, 71, 94, 117, 140 and 152 youre ID

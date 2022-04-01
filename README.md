# vMixTallyLIghtJ
This Tally light works of Vmix web controller.

Make sure it is activate.

Make sure your mixer computer has a static IP address

------

Works fine using Wemos D1.

You use pins D1, D2, D3, D4,

D1 = Red LED  (live)

D2 = Yellow LED (preview)

D3 = Blue LED (connected, but not on preview or live)

D4 = Wemos D1 is On 

----

Look for this code to add your Wifi Address and Password. 

char wifiSSD[] = "SSID"; //change Wifi network
char wifiPassword[] = "Password"; //and Wifi Password

int selectCamera = 1; // and camera
String PCaddress = "http://192.168.68.216:8088"; //and address and port



Created by Jay Barrios


# PylontechTasmota
### Pylontech using Tasmota

The purpose of this repository is to help you to read the status of Pylontech battery using Tasmota <br />
Unfortunately there is noty a STD tasmote firmware which has all the required features we need, which means we have to compile a fresh one with the right features <br />
Start a new workspace in Gitpod here: https://gitpod.io/new#https://github.com/arendst/Tasmota <br />
Open /tasmota/user_config_override.h <br />
Edit this file with the parts from the Mods_user_config_override.h Simply cut and paste from this page<br />
https://github.com/krulkip/PylontechTasmota/blob/f4eebe08689806caace1d27da7f744459dc9891e/Mods_user_config_override#L1-L29
This file you can find here https://github.com/krulkip/PylontechTasmota/blob/main/Mods_user_config_override <br />
After the following prompt at the bottom of the page /workspace/Tasmota (development) $ type platformio run -e tasmota <br />
After the compile has completed a file will appear under build_output/firmware called firmware.bin<br />
Program your ESP8266 with that code. I use tasmotiser for that. You simply select this bin file and make sure the settings for self resetting device is set correctly <br />
The firmware activates Display-LCD and Scripting language amongst other things. <br />
Open up home assistant and install Mosquitto. Then install Tasmota. Your tasmota instance will be found in home assistant. <br />
Going to the tasmota instance you can hover over the visit link and see the IP adress of your tasmota device. <br />
Once loaded find the ip and go to it in a webbrowser.<br />
Your screen will look something like below. <br />
<img src="/Tasmota1.jpg" width="100" height="100"><br />
Click on the configure button. This will take you to a new page with possibilituies. <br />
There you will see possibilities to change friendly name etc.
Under 

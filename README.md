# PylontechTasmota
### Pylontech using Tasmota

Read status of Pylontech battery using Tasmota <br />
Start a new workspace here: https://gitpod.io/new#https://github.com/arendst/Tasmota <br />
Open /tasmota/user_config_override.h <br />
Edit this file with the parts from the Mods_user_config_override.h <br />
https://github.com/krulkip/PylontechTasmota/blob/f4eebe08689806caace1d27da7f744459dc9891e/Mods_user_config_override#L1-L29
This file you can find here https://github.com/krulkip/PylontechTasmota/blob/main/Mods_user_config_override <br />
After the following prompt at the bottom of the page /workspace/Tasmota (development) $ type platformio run -e tasmota <br />
After the compile has completed a file will appear under Program your ESP8266 with that code. It activates Display-LCD and Scripting language amongst other things. <br />
<font color="red">This is some text!</font>
Once loaded find the ip and go to it in a webbrowser. You can use home assistant tasmota add-inn for example to find it.
There you will see possibilities to change friendly name etc.
Under 

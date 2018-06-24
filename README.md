Make IOT Weather Station using the ESP8266


1. Hardware Required : ESP8266 board , USB- Serial Converter , Jumper Wires , DH11 (Temperature and Humidity Sensor)
2. Software : Arduino IDE 

Steps 

1. Connect the ESP8266 with the USB to serial converter 
   //http://forum.hobbycomponents.com/viewtopic.php?f=110&t=2056
  
![alt text](http://hobbycomponents.com/images/forum/ESP12E_USB_Connections.png)
2. Connect ESP8266 with DH11 module    
   http://www.instructables.com/id/Interface-DHT11-Humidity-Sensor-Using-NodeMCU/
   connect the 3 pins on the esp8266 board with the corresponding pins on DH11 module as shown 
 
3. Upload the code - While uploading the code make sure keep the flash(yellow block) on 2 pins otherwise espcomm_upload_mem failed error will be faced. 

4. How to get API key : 
 Make an account on thingspeak.com
 Go to my profile 
 Press on Genereate API key and add it to the code 
 
 
5. To create a channel on ThingSpeak 
1. go to My Channels 
2. Cick on New Channel 
3. In the field names set 
   field 1. Temperature
   field 2. Humidity

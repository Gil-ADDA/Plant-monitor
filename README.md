
# Overview
personal plant monitor to keep my lovley plant alive - with monitoring air temperature, air humidity, soil moisture. 
the choosen plant is ficus moclame pyramid https://www.patchplants.com/gb/en/plants/ficus-microcarpa-moclame-780/ 

# Plant-monitor adisional parts 
1. 2 nails as a soil pin
2. wierd for connecting the nails to the Feather Huzzah  





# Hardware 
 1. Adafruit Feather HUZZAH ESP8266  Wifi 
 To convert the data to be analog and send that to the MQTT server  


2. Raspberry Pi 4
 play as a computer

3. DHT 22 Sensor temperature and humidity sensor
 
 
 # software backend 
 telegraf is the reader of the data that install on the Raspberry pi. 
 the telegraf gather the data from the MQTT Broker and send that to the Influxdb 
 
 Influxdb is the database that store the data and  
  
 grafana useing as a display for the data that came from the Influxdb 
 grafana analyze the data and allow to make query and display dashboards with the key data 
 
 what is the diffrent between thouse platform ? 
 
 # The Arcitecture
 
 
 # About the data 
 the data store in the InfluxDB that convert by telegraf.
 
 
 


# hello world 
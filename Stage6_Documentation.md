
# Plant Monitoring System


# 1.0 Problem Statement
For optimal growth, plants need the right attention and care, which includes routinely checking the moisture content of their soil. Additionally, overwatered or underwatered plants may experience stunted development, withering, and demise. Unbalances in soil moisture levels are frequently associated with a variety of plant diseases and pest infestations. In order to enable users to change watering schedules as necessary to maintain ideal soil moisture levels, it is necessary to have a system for monitoring plants that can offer real-time data on the plant's soil moisture levels. Such a system must be simple to use, reasonably priced, and adaptable to various plant species and environmental factors. This research attempts to fill this gap by creating a plant monitoring system that can precisely gauge soil moisture using sensors and IoT technology. This project intends to fill this requirement by creating a plant monitoring system that can specifically assess soil moisture levels using sensors and IoT technology, offering an effective and efficient solution for plant regular upkeep.

# 2.0 System Architecture



The proposed system architecture includes a Wemos D1 ESP32 microcontroller, as well as Soil Moisture Sensor and DHT22 sensors for soil, temperature, and humidity monitoring. The data received by the sensors is then sent to a SQL server using the MQTT protocol, where it is stored in a local database. Finally, the data is visualized using a Grafana dashboard, which provides real-time insights.

# 3.0 Sensors


DHT22 Module (Temperature & Humidity)



Soil Moisture Sensor



# 4.0 Arduino
Make sure Arduino IDE is installed in your PC and add library required for the sensor



## 4.1 Arduino Result


# 5.0 LINUX 

## 5.1 Local Python-based Web Server
Install python3 in terminal
Install Django in the terminal. You must use Ubuntu on your own laptop/PC.
Show the most straightforward web page possible.

## 5.2 Data Ingestion
Sending data to the server
Using the IoT edge device/node/"thing" send some data to your server. 
Data can be anything. Time/temperature/random sequence of numbers etc
The Django/Flask server should catch the data and store it (ingest it)


INITIATE SERVER



DJANGO




## 5.3 Show live data on server

Instal MQTT
Install SQL


SQL DATABASE














DJANGO



INITIATE HUMIDITY 


			


## 5.4 Show live data on the updated server

### 5.4.1 GRAFANA 

Install GRAFANA in terminal

GRAFANA DASHBOARD










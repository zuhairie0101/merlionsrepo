
# Plant Monitoring System


# 1.0 Problem Statement
For optimal growth, plants need the right attention and care, which includes routinely checking the moisture content of their soil. Additionally, overwatered or underwatered plants may experience stunted development, withering, and demise. Unbalances in soil moisture levels are frequently associated with a variety of plant diseases and pest infestations. In order to enable users to change watering schedules as necessary to maintain ideal soil moisture levels, it is necessary to have a system for monitoring plants that can offer real-time data on the plant's soil moisture levels. Such a system must be simple to use, reasonably priced, and adaptable to various plant species and environmental factors. This research attempts to fill this gap by creating a plant monitoring system that can precisely gauge soil moisture using sensors and IoT technology. This project intends to fill this requirement by creating a plant monitoring system that can specifically assess soil moisture levels using sensors and IoT technology, offering an effective and efficient solution for plant regular upkeep.

# 2.0 System Architecture

![unnamed](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/1369d138-28d3-4c93-9f54-3eebf6feb239)


The proposed system architecture includes a Wemos D1 ESP32 microcontroller, as well as Soil Moisture Sensor and DHT22 sensors for soil, temperature, and humidity monitoring. The data received by the sensors is then sent to a SQL server using the MQTT protocol, where it is stored in a local database. Finally, the data is visualized using a Grafana dashboard, which provides real-time insights.

# 3.0 Sensors

![unnamed (1)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/9f0b93c5-97d9-4ced-ae0a-30c9885c603d)

DHT22 Module (Temperature & Humidity)


![unnamed (2)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/9f6d8139-8035-419d-9947-edfdd3b89d76)

Soil Moisture Sensor



# 4.0 Arduino
Make sure Arduino IDE is installed in your PC and add library required for the sensor



## 4.1 Arduino Result
![unnamed (3)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/abdd4229-1685-4d45-9884-233a1491e899)


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

![unnamed (4)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/219db0d6-98de-47c8-86fc-d5da15f24f73)



DJANGO

![unnamed (5)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/c942c0e1-7438-44ba-abd7-dbce5be26c84)




## 5.3 Show live data on server

Instal MQTT
Install SQL


SQL DATABASE

![unnamed (6)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/55a307f7-1f86-4eef-87b8-6886183ebf28)

![unnamed (7)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/f4d98aff-b993-44f8-9992-ba5182d3973f)

![unnamed (8)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/7388348f-074f-4a03-b57c-f636a8f743ba)

![unnamed (9)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/a816a2fa-a903-4077-9f7c-2b1266f4b5e6)











DJANGO



INITIATE HUMIDITY 

![unnamed (10)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/90f7a745-6f78-4a2e-a81f-7df24b9e3dd8)


			


## 5.4 Show live data on the updated server

### 5.4.1 GRAFANA 

Install GRAFANA in terminal

GRAFANA DASHBOARD

![unnamed (11)](https://github.com/zuhairie0101/merlionsrepo/assets/111034231/6cd8950f-9bee-4979-b680-1baaf3649499)










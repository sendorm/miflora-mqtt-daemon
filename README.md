# Xiaomi Mi Flora Plant Sensor MQTT Client/Daemon

Edited from https://github.com/aqualx/miflora-mqtt-daemon/tree/mitempbt

Added: period_mt to config to enable Xiaomi Mijia Temperature and Humidity Sensor refresh rate.

Added: retain=True to homeassistant mqtt service.

The values of period and period_mt should be integer multiplies of each other to get most accurate refresh times. 


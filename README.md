# Fossibot-2400-BT2MQTT
Fossibot 2400 connection via ESP32 Bluetooth to Mqtt

Put your WLAN SSID and Password and your IP address of your MQTT Server and Port in the yaml file and flash it. It should send Data every 3 minutes.

If you want another period change (eg 30 seconds):


fbot:
  id: fbot_id
  ble_client_id: fossibot_ble
  polling_interval: 30s


Usage for eg **IOBroker**

the yaml-source is from here: https://github.com/ylianst/esp-fbot


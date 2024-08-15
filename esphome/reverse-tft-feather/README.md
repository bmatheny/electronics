# ESPHome configuration for the Adafruit ESP32-S2 Reverse TFT Feather

This is an example ESPHome configuration for the [Adafruit ESP32-S2 Reverse TFT Feather](https://learn.adafruit.com/esp32-s2-reverse-tft-feather/overview).

The primary references I pulled from to put this together were:

* [pinout](https://learn.adafruit.com/esp32-s2-reverse-tft-feather/pinouts)
* [WellSeemsToMe on reddit](https://www.reddit.com/r/Esphome/comments/11xmz0w/comment/jggj9f0/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
* [waterproof on the ha forums](https://community.home-assistant.io/t/recipe-esphome-adafruit-feather-esp32-s2-thinkink-e-paper-display-battery-monitor/715683#esphome-yaml-file-3)

# What Works?

* TFT Display
* WiFi
* NeoPixel
* Red LED
* D0, D1, and D2 buttons

# What doesn't work?

These probably work but I don't use them so I haven't included them in the configurations.

* MAX17048 Battery Monitor - This appears like it can work with a [custom component](https://github.com/Option-Zero/esphome-components/tree/max17048/components/max17048)
* BME280 Temperature, Humidity and Pressure Sensor - Untested, it doesn't ship with the board and I didn't need it
* STEMMA QT - I don't use it

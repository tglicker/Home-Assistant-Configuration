# Home-Assistant-Configuration
[Home Assistant](https://home-assistant.io/) configuration files (YAMLs). These are my Home Assistant configuration files.

# Devices
* [Raspberry Pi 3](http://amzn.to/2nMYhkX) - Hass.io Installed
* [Aeotec Z-Stick Gen5](http://aeotec.com/z-wave-usb-stick)
* [Synology DSM1815+ 8 Bay NAS](http://amzn.to/2ooPHdn)
* [Reolink RLC-422-P IP Camera](http://amzn.to/2n0rHgs) x2
* [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor)
* [Fibaro Relay Switch](https://www.fibaro.com/en/products/switches-2) - Light Switch Control
* BroadLink SP Mini 3 x4 - Power Socket Control
* [Milight WiFi Gateway Emulator](https://github.com/sidoh/esp8266_milight_hub) (NodeMCU ESP8266 / NRF24L01+ module) - Allows for controlling an unlimited amount of LimitlessLED Light groups via MQTT Protocol
* [LimitlessLED Full Color and Dual White Downlight](http://www.limitlessled.com/shop/mr16-rgbw-ww-cw-color-and-white-led) - Smart Dimmable Full Color Downlights
* [LimitlessLED Remote Control](http://www.limitlessled.com/shop/remote-control-for-rgb-ww-cw-color-led-lightbulbs) - Smart Light Remote Control [HASS Integrated](https://github.com/sidoh/esp8266_milight_hub/wiki/Using-Milight-Remote-with-HomeAssistant)
* [Xiaomi Mijia Smart LED Desk Lamp](http://www.gearbest.com/table-lamps/pp_363779.html)
* [Google Home](https://madeby.google.com/home) - Voice Assistant/Control
* [Google Chromecast 1](https://www.google.com.au/chromecast/tv/chromecast)
* [Google Chromecast 2](https://www.google.com.au/chromecast/tv/chromecast)
* [Google Chromecast Audio](https://www.google.com.au/intl/en_au/chromecast/audio)
* [Harmony Hub](http://amzn.to/2n0jhG3) - TV and AC Control
* [OwnTracks App](http://owntracks.org) - Mobile Device Tracking
* [Plex Media Server](https://plex.tv) - Media Streaming

# Automations
* Stream radio stations onto Chromecasts and control their volume.
* On motion from [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor) turn on lights.
* Burgular notifications from [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor)
* Temperature notification from [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor) if no one is home and the home temperature is above 23°C at 5PM. - Option to start the Air Conditioner.
* AC Split System control via [Harmony Hub](http://amzn.to/2n0jhG3).
* Living Room TV Activity control via [Harmony Hub](http://amzn.to/2n0jhG3).
* Change Home Assistant to a dark theme at sunset and back to the light theme at sunrise.
* Hide Media Players from the Home Assistant Default View when not being used.
* IFTTT control of the Office [Xiaomi Mijia Smart LED Desk Lamp](http://www.gearbest.com/table-lamps/pp_363779.html)
* Media Player light control in Living Room - Currently in testing.
* [LimitlessLED Remote Control](http://www.limitlessled.com/shop/remote-control-for-rgb-ww-cw-color-led-lightbulbs) forwarding to ensure Home Assistant doesn't lose sync whilst using it.
* Turn on Entryway light for 10 minutes once I get home.
* Weather notification at sunrise and sunset.

# Screenshots
#### Day Theme
![Home](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA1.PNG)
![Outside](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA2.PNG)
![Lights](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA3.PNG)
![Other](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA4.PNG)
#### Night Theme
![Night](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HANIGHT.PNG)
#### HA Floorplan
![HA Floorplan](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HAFLOORPLAN.PNG)

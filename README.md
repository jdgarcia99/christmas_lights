# christmas_lights

## Overview
ESP8266 convert for Muvit IO [MIOGAR001](https://www.innov8iberia.com/tira-led/6154-muvit-io-guirnalda-decorativa-wifi-rgb-6m60-led-2m-de----cable-power-line-8426801164321.html) Christmas Smart Lights

I recently bought a Muvit IO MIOGAR001 Christmas Smart Lights. These leds are tuya based implementation with the WBS2 chip and had wifi and bluetooth connectivity. Several effects incorporated and maneagable throught the smartlife app.

I wanted to have these lights integrated within my HA instance. Tuya component offets a pretty basic compatibility with just ON and OFF capabilities.

Although the lights are fine have two major problems from my point of view:
* WIFI connectivity is pretty inconsistent. Lots of wifi disconnections forcing you to unplug/plug again the device
* Basic integration with Home Assistant. Because the previous problem, the management of these lights is pretty unreliable
* Cloud based solution, mandatory to pass through Tuya cloud. I wanted to avoid this and have full local control

After looking at this thread
https://community.home-assistant.io/t/mirabella-genio-smart-home/85816/171, I decided to make my own modification of the device for better control

## The device





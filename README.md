# Home-Assistant
HomeAssistant (HASS)

## List Of Devices
### Zwave Items
* Smart Plug Dimmer
  * https://products.z-wavealliance.org/products/2358
* Power Strip
  * 
* Inovelli On/Off
* Inovelli Dimmer
* Inovelli Bulbs

## Quick Notes/Reminders/Links
### Path to configuration.yaml:
/home/homeassistant/.homeassistant

### Restart HASS Service:
sudo systemctl restart home-assistant@homeassistant.service

### Update Steps:
https://www.home-assistant.io/docs/installation/virtualenv#upgrade
https://www.home-assistant.io/docs/installation/raspberry-pi/#updating

1. sudo su - homeassistant
2. source /srv/homeassistant/bin/activate
3. python3 -m pip install --upgrade homeassistant
   * or pip3 install --upgrade homeassistant

### HASS-CLI
https://github.com/home-assistant/home-assistant-cli


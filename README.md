# OpenEPaperLink-HA-Christmas-Countdown
Count down the days till Christmas Day! All images are pulled down from an external server at https://www.chunkymedia.co.uk - keep you surprised! 

<img src="20231219_091339_resized.jpg" width="50%" alt="Epaper Tag using the Christmas Countdown!">

Set the date of Christmas in the automation variable `days_until_xmas`. 
The text used is 'Days 'till Christmas', 'Day 'till Christmas', and 'Merry Christmas' - adjust according to your local language. Edit automation in YAML.

Home Assistant and a working [OpenEpaper](https://openepaperlink.de/) setup, with HA Integration - https://github.com/jonasniesner/open_epaper_link_homeassistant

## Sensors/Integrations needed:

* https://github.com/jonasniesner/open_epaper_link_homeassistant (Install via HACS)

## Installation
* Add font `GothamRnd-Bold.ttf` to `/config/media` Home Assistant (create the folder "media" too).
* Add contents of `automation-2.9-xmas-countdown.yaml` (2.9") to a new automation in Home Assistant (Choose "Edit in Yaml" from top right three dots in a new automation). The automation is using a time template of every 00:05 time - adjust according to taste!

## Customizing
### Date
Set the date of Christmas in the automation variable `days_until_xmas` e.g. '12/25/2023'

### Text
The text used is 'Days 'till Christmas', 'Day 'till Christmas', and 'Merry Christmas' - adjust according to your local language.

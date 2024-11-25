# OpenEPaperLink-HA-Christmas-Countdown
Count down the days till Christmas Day! All images are pulled down from an external server at https://www.chunkymedia.co.uk - to keep you surprised (don't look!)!  

<img src="20231219_091339_resized.jpg" width="50%" alt="Epaper Tag using the Christmas Countdown!">

<img src="20231219_091339_resized.jpg" width="50%" alt="Epaper Tag using the Christmas Countdown - 4.2 version!">


The date of Christmas is set in the variable `days_until_xmas` and shouldn't need altering year on year. 
The text used is 'Days 'till Christmas', 'Day 'till Christmas', and 'Merry Christmas' - adjust according to your local language. Edit automation in YAML.

Home Assistant and a working [OpenEpaper](https://openepaperlink.de/) setup, with HA Integration - https://github.com/jonasniesner/open_epaper_link_homeassistant

## Sensors/Integrations needed:

* https://github.com/jonasniesner/open_epaper_link_homeassistant (Install via HACS)

## Installation
* Add font `GothamRnd-Bold.ttf` to `/config/media` Home Assistant (create the folder "media" too).
* Add contents of `automation-2.9-xmas-countdown.yaml` (2.9") or `automation-4.2-xmas-countdown.yaml` (4.2") to a new automation in Home Assistant (Choose "Edit in Yaml" from top right three dots in a new automation). The automation is using a time template of 00:01:00 time - adjust according to taste!

## Customizing
### Date
The date of Christmas is set in the variable `days_until_xmas` and shouldn't need altering year on year. 

### Text
The text used is 'Days 'till Christmas', 'Day 'till Christmas', and 'Merry Christmas' - adjust according to your local language. The Date day of week and month (4.2" version) should be pulled in via your local HA language, so shouldn't need editing.

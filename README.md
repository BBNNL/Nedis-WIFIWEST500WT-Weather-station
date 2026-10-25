# Nedis-WIFIWEST500WT-Weather-station
I made a custom configuration for the Nedis WIFIWEST500WT weather station on the base of Jampie85. 


It works throug Tuya_Local to make it work in Home Assistant. https://github.com/make-all/tuya-local.
There maybe more brands with the same model. To me, it was recognized as the EM3390TF weather station.

<img width="592" height="511" alt="image" src="https://github.com/user-attachments/assets/eebe6362-5dea-4d24-bbca-f37c4f498a1a" />
<img width="310" height="580" alt="image" src="https://github.com/user-attachments/assets/aa75c0c5-acb6-4a35-b248-2d908aa22af8" />

In Dutch.

<img width="535" height="741" alt="image" src="https://github.com/user-attachments/assets/6d25909d-20f7-415b-b716-57aa018be528" />



Protocol version: 3.5
Brand: Nedis
Model: WIFIWEST500WT
Sold by Action in The Netherlands.


# Yaml card file

title: Weerstation
type: entities
entities:
  - entity: sensor.nedis_wifiwest500wt_weather_station_comfort
    name: Comfort
  - entity: sensor.nedis_wifiwest500wt_weather_station_indoor_temperature
    name: Binnen temperatuur
  - entity: sensor.nedis_wifiwest500wt_weather_station_indoor_humidity
    name: Luchtvochtigheid binnen
  - entity: sensor.nedis_wifiwest500wt_weather_station_outdoor_temperature
    name: Buiten temperatuur
  - entity: sensor.nedis_wifiwest500wt_weather_station_outdoor_humidity
    name: Luchtvochtigheid buiten
  - entity: sensor.woonkamer_weerstation_atmosferische_druk
    name: Luchtdruk
  - entity: sensor.woonkamer_weerstation_neerslagintensiteit
    name: Regen laatste uur
  - entity: sensor.woonkamer_weerstation_neerslag
    name: Regen vandaag
  - entity: sensor.windrichting_kompas
    name: Windrichting
  - entity: sensor.woonkamer_weerstation_windsnelheid
    name: Windsnelheid
  - entity: sensor.woonkamer_weerstation_gust
    name: Windvlaag
  - entity: sensor.windkracht_2
    name: Windkracht
  - entity: sensor.windstoot
    name: Windkracht windvlaag


# In Local Tuya use.

<img width="379" height="176" alt="image" src="https://github.com/user-attachments/assets/068a9a1c-ea60-48cd-a5e1-ad23bd72578f" />
For the template, you can check out https://github.com/make-all/tuya-local/discussions/4136


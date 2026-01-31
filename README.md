# Nedis-WIFIWEST500WT-Weather-station
I made a custom configuration for the Nedis WIFIWEST500WT weather station on the base of Jampie85. 
https://github.com/make-all/tuya-local/discussions/4136


It works throug Local Tuya to make it work in Home Assistant. https://github.com/make-all/tuya-local.
There maybe more brands with the same model.

<img width="592" height="511" alt="image" src="https://github.com/user-attachments/assets/eebe6362-5dea-4d24-bbca-f37c4f498a1a" />
<img width="310" height="580" alt="image" src="https://github.com/user-attachments/assets/aa75c0c5-acb6-4a35-b248-2d908aa22af8" />

In Dutch.

<img width="485" height="530" alt="image" src="https://github.com/user-attachments/assets/761956d2-c57c-4840-a28f-aee624fc4429" />


Protocol version: 3.5
Brand: Nedis
Model: WIFIWEST500WT
Sold by Action in The Netherlands.


# Yaml file

type: grid
cards:
  - type: heading
    heading_style: title
    heading: Weerstation
  - type: entities
    entities:
      - entity: sensor.weerstation_comfort
        secondary_info: none
        name: Comfort
        icon: "mdi:"
      - entity: sensor.weerstation
        name: Binnen temperatuur
      - entity: sensor.weerstation_indoor_humidity
        name: Luchtvochtigheid binnen
      - entity: sensor.weerstation_outdoor_temperature
        name: Buiten temperatuur
      - entity: sensor.weerstation_outdoor_humidity
        name: Luchtvochtigheid buiten
      - entity: sensor.weerstation_pressure
        name: Luchtdruk
      - entity: sensor.weerstation_rain_last_hour
        name: Regen laatste uur
      - entity: sensor.weerstation_rain_today
        name: Regen vandaag
      - entity: sensor.weerstation_wind_direction
        name: Wind richting
      - entity: sensor.weerstation_wind_speed_avg
        name: Windkracht
      - entity: sensor.weerstation_wind_gust
        name: Windvlaag


# In Local Tuya use.

<img width="379" height="176" alt="image" src="https://github.com/user-attachments/assets/068a9a1c-ea60-48cd-a5e1-ad23bd72578f" />


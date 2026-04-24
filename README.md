# Kristoffer Kolumbuksen jaljilla - Country Guessing Game

A browser-based country guessing game where the player tries to find the "missing" Christopher Columbus using distance and compass-direction hints.
This README is written from a published product perspective.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Flask](https://img.shields.io/badge/Flask-3.x-black)
![MySQL](https://img.shields.io/badge/MySQL-8.x-0F5D9C)
![Deploy](https://img.shields.io/badge/Deploy-Render-46E3B7)

## Published Version

- Live site: [https://lentokonepeli.onrender.com](https://maanarvauspeli.onrender.com)
- Source repository: [https://github.com/roopeaal/Maanarvauspeli](https://github.com/roopeaal/Maanarvauspeli)
- Hosting platform: Render (Free Web Service)
- Database: Aiven MySQL (SSL connection)

## Product Features

- Interactive world map with clickable countries.
- Country guessing by typing or map clicking.
- Typo-tolerant input with country suggestions.
- Dynamic scoring and hint system.
- Themed antique-map visual style.
- Top 10 leaderboard view.
- Mobile-optimized UI.

## Production Tech Stack

- Backend: Flask + Gunicorn
- Frontend: Jinja2, CSS, JavaScript
- Map: Leaflet + GeoJSON
- Geospatial calculations: geopy
- Database driver: mysql-connector-python

## Production Notes

- The app is deployed on Render Free.
- Free services can spin down after inactivity.
- First load after inactivity may take around 30-90 seconds (cold start), after which the game runs normally.

## License and Attributions

The antique world-map background image is public domain from Wikimedia Commons:
https://commons.wikimedia.org/wiki/File:Antique_World_Map_of_Continents_and_Oceans_1700.png

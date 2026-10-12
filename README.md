# Skyline Weather Forecast

A responsive, single-page weather app that shows current conditions, the next 24 hours, and a five-day forecast for a searched city. It can also use the browser's location permission to show nearby weather.

## Run locally

No build tools or dependencies are required. Open `index.html` in a browser, or serve this folder with a local web server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

The app fetches city names and weather data from the free [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api) and [Forecast API](https://open-meteo.com/en/docs). An internet connection is required. Browser location access may require HTTPS or localhost.

## Features

- Search for a city and view its current weather
- Browse an hourly forecast and a five-day outlook
- View temperature, humidity, wind, and precipitation chances
- Optionally use browser location services
- Responsive layout with no third-party JavaScript dependencies

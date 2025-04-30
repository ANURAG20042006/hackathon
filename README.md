# 🌦️ Weather App – Real-Time & Historical Weather Checker

This is a responsive and animated weather web app that lets users check real-time and historical weather data using the [WeatherAPI.com](https://www.weatherapi.com/) service. It supports geolocation, custom city searches, and date-specific forecasts with interactive visuals and dynamic UI effects.

## 🚀 Features

- 🌍 **Geolocation Detection**: Automatically fetches weather based on user's current location.
- 🌤 **Real-Time Weather**: Fetches live temperature, condition, AQI, humidity, wind, and rain chance.
- 📅 **Date-Based Forecast**: Select a specific date to view forecast or historical data.
- ⛅ **Dynamic UI Effects**: Background color, weather icons, and animations adapt based on:
  - Temperature
  - Time of day (sun/moon/stars)
  - Weather conditions (rain, snow, fog, etc.)
- 💾 **LocalStorage**: Saves last searched location for user convenience.
- 🎨 **Beautiful UI**: Gradient background, hover animations, shadows, and more.

## 🛠️ Tech Stack

- **HTML5**, **CSS3**
- **Vanilla JavaScript**
- **WeatherAPI.com** – For real-time and historical weather data

## 📸 Screenshots

> *(Add screenshots or a screen recording of your app here)*

## 🧠 How It Works

1. User enters a city or lets the app detect their location.
2. Fetch requests are made to the WeatherAPI endpoints:
   - `/current.json` – for real-time weather
   - `/forecast.json` – for upcoming days
   - `/history.json` – for historical weather (based on date input)
3. Data is parsed and visually rendered with matching effects and icons.

## 🔧 Setup Instructions

1. Clone this repo or open `weather.html` directly in a browser.
2. Replace the `apiKey` in the JavaScript with your own from [WeatherAPI.com](https://www.weatherapi.com/).
3. That’s it! The app is ready to use.

```js
const apiKey = "YOUR_API_KEY_HERE";

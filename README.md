# SkyCast — Weather & Play

A responsive weather dashboard with a built-in weather quiz mini-game. Built with plain HTML, CSS and JavaScript. No Node.js and no API key are required for the demo.

## Features
- Search a city and load current conditions
- Optional device location (browser permission required; works on HTTPS)
- Current temperature, feels-like temperature, humidity, wind and UV index
- 5-day forecast
- Celsius/Fahrenheit toggle
- Weather Wizard quiz with score and streak
- Responsive dark glassmorphism design

## Run locally
1. Download and extract the ZIP.
2. Open `index.html` in a modern browser.
3. If the browser blocks network requests from a local file, use GitHub Pages or a simple local static server.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for deployment and open the URL shown in the Pages section.

## Weather data
Uses the public Open-Meteo geocoding and forecast APIs. Network access is required. Service availability and data coverage can vary.

## Important limitations
This is a front-end demo, not a severe-weather alert service. Do not rely on it for emergency decisions. No accounts or cloud database are included. If you later add user accounts, saved favourites, shared data, or automatic cloud backups, connect a properly secured backend/database. Never put private API keys in client-side JavaScript.

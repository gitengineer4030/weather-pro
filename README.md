<div align="center">

# 🌦️ WeatherPro

### Beautiful, location-aware weather forecasts

Search for a city or use your current location to view current conditions, weather details, and forecasts in a clean web interface.

[View Repository](https://github.com/gitengineer4030/weather-pro) · [Report an Issue](https://github.com/gitengineer4030/weather-pro/issues)

</div>

---

## 📖 About

**WeatherPro** is a browser-based weather application built with HTML, CSS, and JavaScript. It uses the [Open-Meteo](https://open-meteo.com/) geocoding and forecast APIs to find places and retrieve weather information.

Search for a location, select a suggested place, or allow browser location access to see the weather for where you are.

## ✨ Features

- **Current weather** — current temperature, weather condition, and wind information.
- **City search** — search for a city by name.
- **Location suggestions** — view matching places while typing and select a result.
- **Use My Location** — request your device's location through the browser's Geolocation API.
- **24-hour forecast** — hourly temperatures, weather conditions, precipitation probability, and wind speed.
- **5-day forecast** — daily high and low temperatures, conditions, precipitation probability, and maximum wind speed.
- **Weather details** — humidity, visibility, UV index, sunrise, and sunset.
- **Responsive interface** — styling intended to make the dashboard usable across screen sizes.
- **Loading and error states** — feedback while weather data loads and when a request fails.

Weather data availability and individual displayed values depend on the upstream service and browser environment.

## 🛠️ Built With

- **HTML5** — page structure
- **CSS3** — layout and styling
- **JavaScript** — search, API requests, and rendering weather information
- **Open-Meteo Geocoding API** — city and place search
- **Open-Meteo Forecast API** — weather and forecast data
- **Google Fonts (Inter)** — typography
- **Font Awesome** — interface icons

The project is a static front-end application; no Node.js installation or build step is required for basic local use.

## 🗂️ Project Structure

```text
weather-pro/
├── index.html   # Main page and interface structure
├── style.css    # Application styles and responsive layout
├── app.js       # Search, location, API calls, and weather rendering
└── README.md    # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser such as Chrome, Edge, Firefox, or Safari
- An internet connection to load weather data and external fonts/icons
- Python (optional, for running a local web server)

### 1. Clone the repository

```bash
git clone https://github.com/gitengineer4030/weather-pro.git
cd weather-pro
```

### 2. Run the application

**Option A — open directly**

Open `index.html` in your browser. City search may work directly, but browser geolocation generally requires a secure context, such as `localhost` or HTTPS.

**Option B — use Python's local server**

From the project folder, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

To stop the server, press `Ctrl+C` in the terminal.

## 🌍 How to Use

1. Open WeatherPro in your browser.
2. Enter a city or location in the search field.
3. Choose a suggestion if one appears, or submit the city search.
4. Alternatively, select **Use My Location** and allow location access when your browser asks.
5. Review the current weather details, 24-hour forecast, and 5-day forecast.

## 🔌 Weather Data and Permissions

- Weather information is requested from the Open-Meteo APIs over the internet.
- City search uses the Open-Meteo geocoding service.
- The location button uses the browser's Geolocation API and requires your permission.
- No Open-Meteo API key is configured in the current front-end code.
- External fonts, icons, and weather icons may be loaded from third-party services.

The application requires an internet connection for live data. If requests fail, check your connection and try again. Review the source code and external services' privacy terms before using the application in a sensitive environment.

## 🧪 Testing Checklist

Before publishing a change, check:

- [ ] The main page loads without JavaScript errors.
- [ ] Searching for a valid city displays weather data.
- [ ] An unknown city produces a helpful message.
- [ ] Location access works when permission is granted.
- [ ] Denied or unavailable location access is handled clearly.
- [ ] Hourly and 5-day forecast sections display data.
- [ ] The layout remains usable on desktop and mobile screens.
- [ ] The page behaves sensibly when the network or weather API is unavailable.

No automated test suite or package-based test command is currently documented.

## 🤝 Contributing

Suggestions, bug reports, and improvements are welcome.

1. Fork the repository.
2. Create a branch for your change.
3. Make a focused update.
4. Test the relevant behavior in a browser.
5. Submit a pull request with a clear summary and testing notes.

For bug reports or feature requests, use [GitHub Issues](https://github.com/gitengineer4030/weather-pro/issues).

## 📄 License

No license file was confirmed in the repository when this README was prepared. Unless a license is added, do not assume that the source code is licensed for unrestricted reuse or redistribution.

## 👤 Maintainer

Created and maintained by [gitengineer4030](https://github.com/gitengineer4030).

---

<div align="center">

Made with ☁️ for a clearer view of the weather.

</div>

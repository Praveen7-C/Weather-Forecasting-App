# Weather Forecasting App

A simple and modern web application for getting real-time weather and a 7-day forecast for any city in the world. This app is built with HTML, CSS, and JavaScript, leveraging popular libraries like Bootstrap and Font Awesome to create a clean and responsive user interface.

---

## Features

* **Search by City**: Enter any city name to get the current weather and upcoming forecast.
* **Use Current Location**: Automatically detects your location using the browser's Geolocation API.
* **Current Weather Details**:

  * Temperature
  * Humidity
  * Wind speed
  * Weather conditions (with icons)
* **Sunrise & Sunset Times**: Displays today's sunrise and sunset.
* **7-Day Forecast**: Includes daily highs/lows and weather conditions.
* **Responsive Design**: Fully mobile-friendly and modern UI with smooth transitions and styling using Bootstrap and custom CSS.

---

## Technologies Used

* **HTML5**
* **CSS3** (Custom + Bootstrap)
* **JavaScript (Vanilla)**
* **Open-Meteo API** for weather and geolocation
* **Font Awesome** for weather icons
* **Bootstrap 5** for responsive layout and modals

---

## API Services

* [Open-Meteo Weather API](https://open-meteo.com/)
* [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)

---

## How to Run the Project

1. **Clone the repository** or download the `.html` file:

   ```bash
   git clone [https://github.com/your-username/weather-forecasting-app.git](https://github.com/Praveen7-C/Weather-Forecasting-App.git)
   ```

2. **Open the HTML file** in any modern browser:

   * No server setup or build tools required.
   * Just open the `index.html` file directly.

---

## Usage Instructions

1. Type a city name in the input field and click **Search**, or press `Enter`.
2. Click the **location icon button** to use your current location.
3. The app will show:

   * City name and date
   * Current temperature, humidity, wind, and condition icon
   * Sunrise and sunset times
   * 7-day forecast with weather icons

---

## UI Highlights

* Clean and minimalist card-style design
* Animated hover effects on forecast cards
* Spinner while data is loading
* Modal dialog for error messages (e.g., invalid city or denied location access)

---

## Limitations

* Forecast limited to 7 days (API limitation)
* Requires internet access to use external APIs and CDN resources
* Weather codes mapped to closest matching Font Awesome icons (may not always be precise)

---

## License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## Acknowledgements

* [Open-Meteo](https://open-meteo.com/) for providing free weather and geocoding APIs
* [Font Awesome](https://fontawesome.com/) for icons
* [Bootstrap](https://getbootstrap.com/) for styling framework

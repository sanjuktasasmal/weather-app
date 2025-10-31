# 🌦️ Weather App

A simple and responsive **Weather App** built using **React.js**, **CSS**, and a public **Weather API**.
It allows users to search for any city and view real-time weather details such as temperature, humidity, wind speed, and weather condition icons.

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays current temperature, humidity, and wind speed
* 🌤️ Dynamic weather icons (Clear, Cloudy, Rainy, etc.)
* 💻 Responsive and clean UI using CSS
* ⚡ Fast and lightweight React app

---

## 🛠️ Technologies Used

* **React.js** – Frontend framework
* **CSS** – Styling and layout
* **Weather API** – For real-time weather data (e.g., [OpenWeatherMap API](https://openweathermap.org/api))

---

## 📦 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/sanjuktasasmal/weather-app.git
   ```
2. **Navigate to the project folder**

   ```bash
   cd weather-app
   ```
3. **Install dependencies**

   ```bash
   npm install
   ```
4. **Add your Weather API key**

   * Create a `.env` file in the project root.
   * Add this line:

     ```
     REACT_APP_API_KEY=your_api_key_here
     ```
5. **Run the app**

   ```bash
   npm run dev
   ```

---

## 🧠 How It Works

1. User enters a city name in the search bar.
2. The app sends a request to the **Weather API** using `fetch()` or `axios`.
3. The API returns real-time weather data.
4. The app updates the UI dynamically to show:

   * Temperature
   * Weather condition icon
   * Humidity
   * Wind speed





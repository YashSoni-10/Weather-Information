# 🌤 Weather App

A simple and responsive **Weather Application** built using **HTML, CSS, and JavaScript** that allows users to check weather conditions for their current location or search for any city worldwide.

---

## 🚀 Features

* 📍 Get **weather of your current location** using Geolocation API
* 🔍 **Search weather by city name**
* 🌡 Displays **temperature, humidity, wind speed, and cloudiness**
* 🌎 Shows **country flag and weather icon**
* ⏳ Loading screen while fetching data
* 📱 Clean and responsive UI

---

## 🛠 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6)**
* **OpenWeather API**

---

## 📦 API Used

Weather data is fetched from:

https://api.openweathermap.org

---

## ⚙️ How It Works

1. The app first asks for **location permission**.
2. If granted, it fetches weather data using **latitude and longitude**.
3. Users can also **search weather by city name**.
4. The app fetches data from the OpenWeather API and displays:

   * Temperature
   * Weather description
   * Wind speed
   * Humidity
   * Cloud coverage

---

## 📂 Project Structure

```
Weather-App
│
├── index.html
├── style.css
├── index.js
└── assets/
    ├── wind.png
    ├── humidity.png
    ├── cloudy.png
    ├── location.png
    └── loading.gif
```

---

## 🖥 Setup & Installation

1. Clone the repository

```
git clone https://github.com/YOUR-USERNAME/weather-app.git
```

2. Navigate to the project folder

```
cd weather-app
```

3. Open **index.html** in your browser.

---

## 🔑 API Key Setup

1. Create an account at **OpenWeather**
2. Generate your **API Key**
3. Replace the API key inside `index.js`

```javascript
const API_KEY = "YOUR_API_KEY";
```

---

## 📸 Preview

Weather app showing:

* Current weather
* City search
* Weather details

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit pull requests.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

⭐ If you like this project, consider **starring the repository**!

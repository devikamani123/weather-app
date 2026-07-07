# 🌦️ Python Weather App

A simple Python Weather App that fetches real-time weather information for any city using the OpenWeatherMap API.

## 📌 Features

- Get current weather by city name
- Display temperature in Celsius
- Shows:
  - Temperature
  - Feels Like Temperature
  - Humidity
  - Pressure
  - Weather Description
  - Wind Speed
- Handles invalid city names

---

## 🛠️ Technologies Used

- Python 3.x
- Requests Library
- OpenWeatherMap API

---

## 📂 Project Structure

```
WeatherApp/
│
├── weather.py
├── README.md
```

---

## 📥 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
```

### 2. Move to the project folder

```bash
cd weather-app
```

### 3. Install the required library

```bash
pip install requests
```

---

## 🔑 Get an API Key

1. Visit https://openweathermap.org/
2. Create a free account.
3. Generate an API key.
4. Open `weather.py`
5. Replace:

```python
API_KEY = "YOUR_API_KEY"
```

with your own API key.

---

## ▶️ Run the Application

```bash
python weather.py
```

Example:

```
Enter City Name: Hyderabad
```

---

## 📷 Sample Output

```
========== WEATHER REPORT ==========
City         : Hyderabad, IN
Temperature  : 30.8 °C
Feels Like   : 33.5 °C
Humidity     : 70%
Pressure     : 1008 hPa
Weather      : Broken Clouds
Wind Speed   : 4.2 m/s
====================================
```

---

## 📚 Requirements

- Python 3.8 or later
- requests library

Install dependencies:

```bash
pip install requests
```

---

## 🚀 Future Improvements

- GUI using Tkinter
- 5-day weather forecast
- Weather icons
- Auto-detect current location
- Dark mode interface
- Save weather history

---

## 👨‍💻 Author

Your Name

---

## 📄 License

This project is open source and available under the MIT License.

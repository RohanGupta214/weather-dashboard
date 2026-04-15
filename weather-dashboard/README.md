# 🌤 Weather Dashboard

A command-line weather dashboard built in Python that shows **live weather data and a 5-day forecast** for any city in the world — using the OpenWeatherMap API.

> **Built by [Your Name] | Class 12 student | Aspiring CS student**

---

## What it does

- Shows **current temperature**, feels-like, high/low, humidity, wind speed, and pressure
- Displays a **5-day forecast** with ASCII bar charts for temperature
- Works for **any city in the world**
- Handles errors cleanly (no internet, invalid city, bad API key)
- Runs entirely in your terminal — no installation of a browser needed

---

## Sample Output

```
=======================================================
  WEATHER DASHBOARD  |  Monday, 14 April 2026  |  03:30 PM
=======================================================

  📍  Mumbai, IN
  🌧  Rain
      Moderate Rain

  🌡   Temperature   :  28.4°C  (feels like 32.1°C)
       High / Low   :  30.0°C  /  26.5°C
  💧  Humidity      :  85%
  💨  Wind Speed    :  14.4 km/h
  📊  Pressure      :  1008 hPa

-------------------------------------------------------
  5-DAY FORECAST
-------------------------------------------------------

  Mon 14 Apr  🌧  Moderate Rain
    ████████████░░░░░░░░  28.4°C
    Humidity: 85%

  Tue 15 Apr  🌦  Light Rain
    ██████████░░░░░░░░░░  27.1°C
    Humidity: 78%

  Wed 16 Apr  ☁️  Overcast Clouds
    ███████████████░░░░░  29.8°C
    Humidity: 72%

  Thu 17 Apr  🌤  Few Clouds
    ████████████████████  31.2°C
    Humidity: 65%

  Fri 18 Apr  ☀️  Clear Sky
    ████████████████████  32.0°C
    Humidity: 60%

=======================================================
  Data from OpenWeatherMap API  |  github.com/[your-username]
=======================================================
```

---

## How to run it

### Step 1 — Clone the repository
```bash
git clone https://github.com/[your-username]/weather-dashboard.git
cd weather-dashboard
```

### Step 2 — Install the dependency
```bash
pip install -r requirements.txt
```

### Step 3 — Get a free API key
1. Go to [openweathermap.org/api](https://openweathermap.org/api)
2. Sign up for a free account
3. Go to your profile → API Keys → copy your key

### Step 4 — Add your API key
Open `weather_dashboard.py` and replace line 37:
```python
API_KEY = "YOUR_API_KEY_HERE"   # <-- paste your key here
```

### Step 5 — Run
```bash
python weather_dashboard.py
```

Then type any city name when prompted.

---

## What I learned building this

- How to make API calls using Python's `requests` library
- How to parse **JSON data** (the format all APIs use)
- How to use **functions** to keep code organised and readable
- How to handle **errors gracefully** so the program doesn't crash
- How to use **f-strings** for clean, readable output
- How to work with **dates and times** using the `datetime` module
- How to read and understand **API documentation**

---

## Technologies used

| Tool | Purpose |
|------|---------|
| Python 3.12 | Core language |
| `requests` | Making HTTP calls to the API |
| `datetime` | Formatting date/time output |
| OpenWeatherMap API | Live weather data (free tier) |

---

## Project structure

```
weather-dashboard/
│
├── weather_dashboard.py    # Main program — all the code lives here
├── requirements.txt        # Libraries needed to run the project
└── README.md               # This file
```

---

## Future improvements (what I plan to add)

- [ ] Save weather history to a CSV file
- [ ] Add support for searching by ZIP code
- [ ] Build a simple web interface using Flask
- [ ] Add unit toggle (Celsius ↔ Fahrenheit)
- [ ] Plot forecast as a graph using matplotlib

---

## Author

**[Your Full Name]**  
Class 12 student | Pathankot, Punjab, India  
Aspiring Computer Science student  

📧 [your email]  
🔗 [your LinkedIn when you make one]

---

*This is my first Python project. I built it to learn how APIs work and to start building a portfolio for university applications.*

# 🌦️ WeatherCLI — Terminal Weather Application

WeatherCLI is a beautifully styled, color-rich command-line application that fetches **real-time weather**, **air quality**, **sunrise/sunset**, and **local timezone info** for any city in the world.  
It uses the **WeatherAPI.com** service and works on **Windows, macOS, and Linux** terminals.

---

## ✨ Features

✓ Real-time temperature (°C)  
✓ Cloud coverage (%)  
✓ Visibility (km)  
✓ Air quality (US-EPA index)  
✓ Sunrise & Sunset times  
✓ Local timezone & formatted local time  
✓ Auto installation of dependencies  
✓ Colorful ASCII UI (thanks to `colorama`)  
✓ Clear terminal UI for every screen  
✓ Created for beginners — simple structure and readable code  

---

## 📦 Requirements

- Python **3.6+**
- WeatherAPI API Key  
  (You can get one for free at https://www.weatherapi.com/)
- Internet connection

---

## 🚀 Installation & Usage

1. **Clone or download this project**
   ```bash
   git clone https://github.com/anonfaded/weatherCLI
   ```
2. Run the script
```bash
python3 weather.py
```

## ⚙️ Configuration
Inside the script, set your WeatherAPI key:
```bash
key = "YOUR_API_KEY_HERE"
```
## 🛠️ Technologies Used
- Python 3
- requests — API calls
- colorama — colored terminal output
- WeatherAPI.com — weather data

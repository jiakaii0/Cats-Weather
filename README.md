# Weather Whiskers 🐾

A playful weather app that blends real-time meteorology with animated cat GIFs.  
Search any city, get live conditions, enjoy a random cat animation, and watch the background adapt dynamically to the weather.

---

## ✨ Features

### 🌤 Real-Time Weather
- Uses **Open-Meteo API** for live temperature and condition data.
- Displays temperature, interpreted weather status, and a matching cat quote.

### 😺 Cat GIF Integration
- Fetches a new cat GIF from **TheCatAPI** for every search.
- Cat quotes change depending on weather and temperature.

### 🌎 City Autocomplete
- Autocomplete powered by **Open-Meteo Geocoding**.
- Shows suggested cities with country flags and region info.
- One-click selection instantly loads the weather.

### 📸 8K Dynamic Backgrounds
- Generates HD city backgrounds using the Pollinations AI endpoint.
- Background adjusts according to:
  - Weather type (clear, cloudy, rain, snow, storm, fog)
  - City name
  - Randomized seed for variation
- Smooth fade transitions between backgrounds.

### ❄️ Rain & Snow Particle Effects
- Canvas-rendered weather particles.
- Rain streaks, snowflakes, or no particles depending on conditions.

### 🔍 Clean UI
- Frosted glass card design.
- Animated loading indicators.
- Clear error handling for invalid or missing cities.
- Responsive layout for desktop and mobile.

---

## 🛠 Tech Stack

| Component | Tech |
|----------|------|
| UI | HTML5 |
| Weather | Open-Meteo API |
| Geocoding | Open-Meteo Search API |
| Cat GIFs | TheCatAPI |
| HD Backgrounds | Pollinations AI |
| Particles | HTML Canvas |

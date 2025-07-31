# API-Based-Weather-Dashboard
This project provides a fully dynamic weather monitoring dashboard in Power BI, using data fetched from the OpenWeatherMap API. It includes real-time current weather data and 5-day/3-hour forecasts for multiple Indian cities. The solution is built entirely using Power Query (M) and DAX without any third-party

Features
  🌍 Live Weather Data: Pulls real-time temperature, humidity, pressure, visibility, wind, sunrise/sunset, and weather condition.
  📅 5-Day Forecast: Visualizes weather forecasts in 3-hour intervals for each city.
  🕒 Time Zone Adjustments: Converts UTC timestamps to local Indian time (IST).
  🌇 Sunrise/Sunset Time: Calculated in local time with proper formatting.
  🌡️ Feels Like, Dew Point, Heat Index (Custom Measures)
  🌧️ Rainfall & Visibility with units in mm and km.
  📊 Line & Bar Charts for temperature, humidity, wind speed, and pressure trends.
  🖼️ Weather Icons: Dynamically shown via image URLs fetched from the API.

🛠️ Technologies Used
  Power BI
  Power Query (M Language)
  DAX (Data Analysis Expressions)
  OpenWeatherMap API (Free Tier)
  JSON Parsing & API Integration

🔗 API Integration
  This dashboard uses:
  OpenWeatherMap Current Weather API
  OpenWeatherMap 5 Day / 3 Hour Forecast API

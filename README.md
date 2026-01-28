# Weather API Application (Python)

## Project Overview
This project is a Python-based console application that fetches real-time weather information for a given city using the OpenWeatherMap API.  
It demonstrates how to integrate external APIs in Python, handle JSON responses, and display useful weather details to the user.

---

## Features
- Fetch real-time weather data
- Search weather by city name
- Displays temperature in Celsius
- Shows humidity and weather condition
- User-friendly console output
- Error handling for invalid city names

---

## Technologies Used
- Python 3
- OpenWeatherMap API
- Requests library
- JSON data handling

---

## API Used
- OpenWeatherMap API (Free tier)

---

## How to Run the Project

### 1️) Prerequisites
- Python 3 installed
- Internet connection
- OpenWeatherMap API key

---

### 2️) Install Required Library
```bash
pip install requests
```

### 3) Setup API Key
Open weather_app.py and replace:

api_key = "YOUR_API_KEY"


with your actual OpenWeatherMap API key.

*Do not expose your real API key in public repositories.

### 4) Run the Application

python weather_app.py

## Program Workflow

- User enters a city name

- Python sends an HTTP request to the OpenWeatherMap API

- API returns weather data in JSON format

- Temperature, humidity, and weather condition are extracted

- Information is displayed to the user

## Sample Output
Enter city name: Mumbai

Weather Report
City: Mumbai
Temperature: 29 °C
Humidity: 65 %
Condition: haze

## Project Structure
weather-api-python/
│
├── weather_app.py
└── README.md

## Learning Outcomes

- Understanding how APIs work

- Making HTTP requests in Python

- Parsing JSON responses

- Handling errors in API calls

- Building real-world Python applications

## Future Enhancements

- 5-day weather forecast

- GUI using Tkinter

- Web application using Flask

- Secure API key using environment variables

## Author

Monika Banothe

## Note

This project is created for learning, practice, and interview preparation purposes.



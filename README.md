# python-weather-app
A desktop weather application built with Python, PyQt5, and the OpenWeather API. Displays temperature, weather conditions, and weather emojis for a user-entered city.

# Python Weather App

## About the Project

This is one of my first Python practice projects, developed while I was learning Python by following a tutorial from Bro Code on YouTube. 

This is a beginner Python project I developed while learning Python and practising how to build desktop applications using APIs.

The application allows users to enter a city name and retrieve current weather information using the OpenWeather API. It displays the temperature in Fahrenheit, a weather emoji, and a description of the current weather conditions.

This project helped me practise Python programming, graphical user interface (GUI) development, API integration, and error handling.

## Features

# Python Weather App 🌦️

A desktop weather application built with Python, PyQt5, and the OpenWeather API. Users can enter a city name to retrieve the current weather, view the temperature in Fahrenheit, and see a weather emoji and description.

## About the Project

I developed this project while learning Python and practicing how to build applications that interact with external APIs.

The project helped me explore graphical user interfaces, HTTP requests, JSON responses, exception handling, and connecting Python applications to online services.

## Features

- Search for current weather by city name.
- Display temperature in Fahrenheit.
- Show a weather description and corresponding emoji.
- Handle common HTTP errors, including invalid city names and API authentication errors.
- Handle connection and request exceptions.
- Provide a simple graphical interface using PyQt5.

## Technologies Used

- **Python** for application logic and data processing
- **PyQt5** for desktop graphical user interface
- **Requests** for HTTP requests to the weather API
- **OpenWeather API** for current weather data

## Application Preview

<img width="525" height="378" alt="Screenshot 2026-10-26 192708" src="https://github.com/user-attachments/assets/afed5584-9d0c-412e-9807-ca95b7a04941" />



## Requirements

- Python 3.10 or newer
- An OpenWeather API key
- An internet connection

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/python-weather-app.git
cd python-weather-app
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install the dependencies

```bash
pip install PyQt5 requests
```

### 3. Configure your API key

Create an account with [OpenWeather](https://openweathermap.org/api) and obtain an API key.

For security, store the key in an environment variable named `OPENWEATHER_API_KEY` instead of writing it directly in the Python source code.

On Windows PowerShell, run:

```powershell
$env:OPENWEATHER_API_KEY="YOUR_API_KEY"
```

Replace `YOUR_API_KEY` with your own key.

### 4. Run the application

```bash
python weather_app.py
```

Make sure the Python code reads the API key from the `OPENWEATHER_API_KEY` environment variable before running the application.

## What I Learned

Through this project, I practiced:

- Building a desktop GUI with PyQt5
- Using classes, methods, and object-oriented programming
- Sending API requests with Python
- Working with JSON responses
- Handling exceptions and HTTP status codes
- Converting temperature values
- Using conditional statements to map weather codes to emojis
- Managing API keys more securely


## Project Status

This is a beginner Python learning project. It is part of my ongoing effort to develop practical programming skills and build a portfolio of projects.


## Python Concepts Practiced

- Variables and data types
- User input and type conversion
- `if`, `elif`, and `else` statements
- Arithmetic operations
- `round()` and formatted output

## How to Run

1. Make sure Python is installed.
2. Clone or download this repository.
3. Open a terminal in the project folder.
4. Run the following command:

   ```bash
   python temperature_converter.py
   ```

## Learning Resource

This project was created as a learning exercise while following the tutorial by Bro Code:

[Python Full Course Program — YouTube](https://www.youtube.com/watch?v=fy5QsDJmctQ)

**Note:** This is a beginner learning project based on a tutorial. It represents an early step in my ongoing Python learning journey.


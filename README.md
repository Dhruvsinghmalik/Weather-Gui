# Weather Data Fetcher

## Overview
The **Weather Data Fetcher** is a Python GUI application built using **Tkinter**. It allows users to fetch real-time weather information for a specified city by leveraging the WeatherAPI service.

## Features
- Simple and intuitive graphical user interface.
- Provides detailed weather information, including:
  - City and country name
  - Temperature in Celsius
  - Weather conditions
  - Humidity level
  - Wind speed
- Error handling for invalid inputs or network issues.

## Prerequisites
1. Python 3.x installed on your system.
2. The `requests` library for making API requests:
   ```bash
   pip install requests
   ```

## Setup
1. Clone or download this repository.
2. Open the `weather_fetcher.py` file in any Python IDE or text editor.
3. Replace the placeholder `api_key` in the code with your WeatherAPI key:
   ```python
   api_key = "your_weather_api_key_here"
   ```
   If you don’t have an API key, you can get one by signing up at [WeatherAPI](https://www.weatherapi.com/).

## How to Run
1. Save the Python script (`weather_fetcher.py`).
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the application:
   ```bash
   python weather_fetcher.py
   ```
5. A GUI window will appear. Enter the city name in the input box and click the **Fetch Weather** button to view the details.

## Example Screenshot
*(You can include a screenshot here if desired.)*

## Error Handling
- If no city name is entered, the application will display an error message: *"Please enter a city name!"*
- If the city is not found or the WeatherAPI returns an error, the application will display the appropriate error message.
- If there is a network or connection issue, an error message with details will appear.

## File Structure
```
weather_fetcher.py    # Main application script
README.md             # Documentation file (this file)
```

## Future Improvements
- Add support for additional weather metrics (e.g., air quality index, sunrise/sunset times).
- Enable saving weather data to a file.
- Enhance the UI with more design elements.

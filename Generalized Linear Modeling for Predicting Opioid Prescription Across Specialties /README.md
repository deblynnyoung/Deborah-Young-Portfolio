Description
The Weather Forecast App is a Python-based application that provides users with real-time weather forecasts. By entering a US city name or ZIP code, users can retrieve current weather conditions, including temperature (in Fahrenheit, Celsius, or Kelvin), minimum and maximum temperatures, and general weather conditions.

Key Features
Location Input: Users can input either a US ZIP code or a city name along with the state code.
Temperature Unit Selection: Offers temperature readings in Fahrenheit, Celsius, or Kelvin.
Real-Time Weather Data: Fetches current weather data from the OpenWeatherMap API.
Error Handling: Includes basic error handling for invalid inputs or API issues.

Requirements
Python 3.x
requests library
An API key from OpenWeatherMap (provided in the script)

Setup and Installation
Ensure Python 3.x is installed on your system.
Install the requests library using pip install requests.
Obtain an API key from OpenWeatherMap and replace api_key in the script with your key.

Usage
Run the script using Python.
Enter a US city name or ZIP code when prompted.
If a city name is entered, also provide the corresponding state code.
Choose the desired temperature unit (Fahrenheit, Celsius, Kelvin).
View the weather forecast displayed on the screen.

Error Handling
The application has basic error handling for common issues such as:
Invalid location input.
Incorrect temperature unit input.
API errors or connectivity issues.

Author: Deborah Young
Last Updated: November 22, 2022

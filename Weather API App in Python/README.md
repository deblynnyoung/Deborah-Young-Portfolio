# Weather Forecast App

## Description
A Python-based application providing real-time weather forecasts. Users can enter a US city name or ZIP code to receive current weather conditions, temperatures, and general weather status.

## Key Features
- **Location Input**: Accepts US ZIP code or city name with state code.
- **Temperature Unit Selection**: Displays temperatures in Fahrenheit, Celsius, or Kelvin.
- **Real-Time Weather Data**: Retrieves data from OpenWeatherMap API.
- **Error Handling**: Manages invalid inputs and API errors.

## Requirements
- Python 3.x
- `requests` library
- OpenWeatherMap API key (included in the script)

## Setup and Installation
1. Install Python 3.x.
2. Run `pip install requests` to install the required library.
3. Get an API key from OpenWeatherMap and insert it into the script.

## Usage
1. Execute the script with Python.
2. Input a US city or ZIP code as prompted.
3. Specify the state code if entering a city name.
4. Select the temperature unit.
5. The weather forecast will be displayed.

## Error Handling
Handles issues like:
- Invalid location inputs.
- Incorrect temperature unit selections.
- API or connectivity errors.

## Author
Deborah Young

## Last Updated
November 22, 2022

# Weather Analysis and Hotel Search WeatherPy | VacationPy

This project is a weather analysis and hotel recommendation tool that helps users find suitable travel destinations based on their weather preferences. It utilizes OpenWeatherMap API to retrieve current weather data and Geoapify API for hotel recommendations.

## Features

- Weather data retrieval: The project allows users to search for weather information of various cities around the world by specifying their desired weather conditions.
- Visualization: The weather data is visualized using interactive maps and plots, making it easier to analyze and compare weather conditions across different cities.
- Hotel recommendations: Based on the weather preferences, the project provides hotel recommendations near each city using Geoapify API.
- Data export: Users can export the analyzed weather data and hotel recommendations to CSV files for further analysis or reference.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies
3. Ensure that you have valid API keys for OpenWeatherMap and Geoapify APIs and create the `api_keys.py` file in the same directory as where you cloned this repository with your keys.
4. api_keys.py structure should be as follows:
   OpenWeatherMap API Key
    weather_api_key = "YOUR KEY HERE"

   Geoapify API Key
    geoapify_key = "YOUR KEY HERE"
6. Run the Jupyter Notebooks
7. Review the generated output files and the analysis and visualization results.
8. Customize the code as needed for your specific use case.


##### All coding used in this project are from week 5 classes, and troubleshooting was done with the assistance of Chat-GPT
### Data for this dataset was generated by edX Boot Camps LLC
### Weather data is sourced from [OpenWeather API](https://openweathermap.org/).
### Hotel recommendations are powered by [Geoapify API](https://www.geoapify.com/).

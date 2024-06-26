# WeatherApp

## Overview
WeatherApp is a simple Android application that displays current weather information based on the user's current location. It fetches weather data from the OpenWeatherMap API and presents it in a user-friendly interface.

## Main Features
- Display current latitude and longitude of the user's location.
- Reverse geocoded address of the user's location.
- Display current system time.
- Display weather information including temperature, humidity, and weather description.
- City search: Users can input a city name to fetch weather data for that specific city.
- Persistent city name: The last searched city name is saved using SharedPreferences and loaded when the app starts.
- Improved networking: Utilized Retrofit library for efficient network operations and handling JSON responses from the OpenWeatherMap API.
- Enhanced user interface: Added a new main screen with an EditText for city input and a Button to fetch weather data. Displayed weather information in a TextView or a CardView for better visualization.

## Getting Started
To get started with WeatherApp, follow these steps:

1. Clone this repository:
git clone https://github.com/HazelLabrooy/WeatherApp.git
2. Obtain an API key from OpenWeatherMap by signing up on their website: [OpenWeatherMap](https://openweathermap.org/)
3. Replace `YOUR_API_KEY` in the `gradle.properties` file with your actual API key.
4. Build and run the application on an emulator or physical device.

## Dependencies
WeatherApp uses the following dependencies:
- Retrofit for networking
- Gson for JSON parsing
- Glide for image loading

## Screenshots
-![weatherApp](https://github.com/HazelLabrooy/WeatherApp/assets/158300148/3980249c-740c-47e9-bb81-0e65497c77c4)
![weather2](https://github.com/HazelLabrooy/WeatherApp/assets/158300148/ebb78b6f-b686-4d9f-b3db-ba58a7d49a01)


## Additional Features
-A user freindly interface for the weather app.
- Added error handling to gracefully handle network errors and display appropriate messages to the user.
- Implemented loading indicators to provide feedback to the user during network requests.

## Credits
- Weather data provided by OpenWeatherMap: [OpenWeatherMap](https://openweathermap.org/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## Weather App Code
This is the zip file of my android studio weather app [WeatherApp](https://github.com/HazelLabrooy/WeatherApp/blob/main/WeatherInformation.zip)
The complete source code of the Android project can be found on GitHub: [CompleteWeatherApp](https://github.com/HazelLabrooy/WeatherApp/blob/main/WeatherInformation_full.zip)


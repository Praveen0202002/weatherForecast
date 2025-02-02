# Weather App

## Description
This Weather App is a simple web application that allows users to check the weather conditions of any city worldwide. The app fetches real-time weather data using the OpenWeatherMap API and displays information such as temperature, humidity, and wind speed.

## Live Demo
Check out the live demo [here](https://praveen0202002.github.io/weatherForecast/).

## Features
- Search for weather information by city name
- Display temperature in Celsius
- Show humidity and wind speed details
- Dynamic weather icons based on current weather conditions
- Error handling for invalid city names

## Technologies Used
- **HTML**: Structuring the web page
- **CSS**: Styling the user interface
- **JavaScript**: Handling API requests and updating the UI dynamically
- **OpenWeatherMap API**: Fetching real-time weather data

## Installation & Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project folder:
   ```sh
   cd weather-app
   ```
3. Open `index.html` in a web browser.

## API Key Configuration
This app requires an API key from [OpenWeatherMap](https://openweathermap.org/). To use your own API key:
1. Sign up at OpenWeatherMap and get a free API key.
2. Replace the existing API key in `logic.js`:
   ```js
   const apiKey = "YOUR_API_KEY_HERE";
   ```

## File Structure
```
weather-app/
│── index.html       # Main HTML file
│── style.css        # CSS for styling the app
│── logic.js         # JavaScript logic for fetching weather data
│── images/          # Folder containing weather icons
```



## License
This project is licensed under the MIT License.




## Weather Dashboard

### Overview
The Weather Dashboard is a React-based web application that provides real-time weather updates, including current weather conditions, daily forecasts, and hourly temperature trends. It fetches weather data using APIs and presents it in a visually appealing format with charts and icons.

### Features
- Search for weather information by city name.
- Get real-time weather data, including temperature, humidity, wind speed, and conditions.
- Display daily and hourly forecasts.
- Show sunrise and sunset times.
- Use geolocation to fetch weather data for the user's current location.
- Visualize hourly temperature trends with a bar chart.
- Display loading indicators while fetching data.

### Technologies Used
- **React** for UI development
- **Recharts** for data visualization (bar charts)
- **React Loader Spinner** for loading indicators
- **Fetch API** for making network requests
- **CSS** for styling

### Installation & Setup
Clone the repository:
```sh
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
```
Install dependencies:
```sh
npm install
```
Start the development server:
```sh
npm start
```
Open your browser and go to `http://localhost:3000`.

### API Keys
This project uses two weather APIs:
- **WeatherAPI** (for current weather details)
- **VisualCrossing API** (for forecast details)

### Setting up API keys:
1. Register on [WeatherAPI](https://www.weatherapi.com/) and get your API key.
2. Register on [VisualCrossing](https://www.visualcrossing.com/) and get your API key.
3. Replace the API keys in the code where necessary.

### Usage
- **Search for a city**: Type the city name in the search box and press `Enter` or click the search icon.
- **Get your location's weather**: Click the `Home` button to use your device's location.
- **View daily forecast**: Scroll down to see the 7-day forecast.
- **View hourly forecast**: Check the bar chart and hourly details below the daily forecast.

### Potential Improvements
- Add more weather details like air quality index and UV index.
- Add more chart visualizations for wind speed and humidity trends.

### License
This project is open-source and available under the MIT License.
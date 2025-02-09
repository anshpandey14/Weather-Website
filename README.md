# Weather Website

This project is a simple weather website built using HTML, CSS, and JavaScript. It fetches real-time weather data from an external API and displays it dynamically on the webpage.

## Features
- Fetches real-time weather data from an API.
- Displays temperature, humidity, wind speed, and weather conditions.
- Search functionality to get weather for any city.
- Responsive design for mobile and desktop.
- Background changes based on weather conditions.

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/anshpandey14/weather-website.git
   ```
2. Navigate to the project folder:
   ```sh
   cd weather-website
   ```
3. Open `index.html` in a web browser.

## API Integration
This project uses the [OpenWeatherMap API](https://openweathermap.org/) to fetch weather data.

### Steps to Get an API Key:
1. Go to [OpenWeatherMap](https://openweathermap.org/).
2. Sign up for an account.
3. Get your API key from the dashboard.
4. Replace `YOUR_API_KEY` in `script.js` with your actual API key.

Example API Call in JavaScript:
```javascript
fetch('https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY')
  .then(response => response.json())
  .then(data => console.log(data));
```

## Project Structure
```
weather-website/
│-- index.html  # Main HTML file
│-- style.css   # CSS for styling
│-- script.js   # JavaScript for API calls and interactivity
│-- README.md   # Project documentation
```

## Future Improvements
- Add a 7-day weather forecast.
- Implement dark mode.
- Improve UI/UX with animations.
- Allow users to save favorite locations.




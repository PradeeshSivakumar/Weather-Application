# Weather App

A responsive web application that provides real-time weather information for any location worldwide using the OpenWeatherMap API.

## Features

- 🔍 **Search by City** - Enter any city name to get current weather information
- 📍 **Geolocation Support** - Get weather for your current location automatically
- 🌡️ **Detailed Weather Info** - Display temperature, humidity, wind speed, and "feels like" temperature
- 🖼️ **Weather Icons** - Visual weather condition indicators
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern UI** - Clean and intuitive user interface

## Project Structure

```
Weather-App/
├── index.html      # Main HTML structure
├── script.js       # JavaScript functionality
├── styles.css      # CSS styling
├── images/         # Image assets
└── README.md       # Project documentation
```

## Technologies Used

- **HTML5** - Page structure and semantic markup
- **CSS3** - Responsive styling and layout
- **JavaScript (Vanilla)** - DOM manipulation and API integration
- **Font Awesome** - Weather and UI icons
- **Google Fonts** - Typography (Poppins font)
- **OpenWeatherMap API** - Real-time weather data

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (to fetch weather data)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HARBA0Ui/Weather-App.git
   cd Weather-App
   ```

2. Start a local server (choose one method):
   
   **Using Python:**
   ```bash
   python -m http.server 8000
   ```
   
   **Using Node.js:**
   ```bash
   npx http-server
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## Usage

1. **Search for a City:**
   - Type the city name in the search input field
   - Click the search button or press Enter
   - Weather information will be displayed

2. **Use Current Location:**
   - Click the location button to get weather for your current location
   - Browser will request permission to access your geolocation
   - Weather will update automatically

3. **View Details:**
   - Temperature in Celsius
   - Weather condition with icon
   - Humidity percentage
   - Wind speed
   - "Feels like" temperature

## API Reference

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) for weather data.

- **Current Weather Endpoint:** `https://api.openweathermap.org/data/2.5/weather`
- **Required Parameters:**
  - `q` - City name (for city search)
  - `lat` - Latitude (for geolocation)
  - `lon` - Longitude (for geolocation)
  - `appid` - API key

## Features in Detail

### Search Functionality
- Real-time weather data fetch
- Input validation
- Error handling for invalid cities

### Geolocation
- Browser geolocation API integration
- Automatic weather update
- User permission handling

### Responsive Design
- Mobile-first approach
- Flexible layout
- Touch-friendly interface

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.

## Author

**HARBA0Ui**

## Acknowledgments

- OpenWeatherMap for weather API
- Font Awesome for icons
- Google Fonts for typography

---

**Note:** The API key included in the code is for demonstration purposes. For production use, consider using environment variables or backend proxying for security.

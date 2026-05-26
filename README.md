# Atmos

Atmos is a modern weather dashboard application built using HTML, CSS, and JavaScript that provides real-time weather insights, 3-day forecast visualization, city search suggestions, geolocation support, and responsive dark/light theme functionality.

The application uses the WeatherAPI service to fetch live weather information and deliver an interactive user experience through a clean and responsive interface.

<img width="1854" height="920" alt="image" src="https://github.com/user-attachments/assets/c64c4ad4-9c1f-44d4-811e-ea562b1a418c" />

## Features

- City search with autocomplete suggestions
- Real-time weather information
- 5-day weather forecast
- Geolocation-based weather detection
- Dark / Light theme toggle
- Theme persistence using localStorage
- Error handling and loading indicators
- Responsive forecast card layout
- Modular JavaScript architecture
- Lightweight frontend-only deployment


## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript (ES Modules)

### API
- WeatherAPI.com

### Application Modules
- `WeatherService.js` → Handles API communication
- `UIHandler.js` → Handles DOM rendering and UI updates
- `main.js` → Core application logic and event handling


## Project Structure

```text
atmos/
│── index.html
│── style.css
│── main.js
│── modules/
│   ├── WeatherService.js
│   └── UIHandler.js
└── README.md
```


## Features Breakdown

### City Search Suggestions

Implements debounced autocomplete functionality for faster and smoother city searching.

### Geolocation Support

Automatically fetches weather information based on the user's current location using browser geolocation APIs.

### Forecast Visualization

Displays weather forecasts with daily weather conditions, icons, and temperature information.

### Theme System

Supports both dark and light themes with persistent user preferences stored using localStorage.

### Responsive Design

Optimized for desktop, tablet, and mobile devices.


## Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/alqamahansari/atmos.git
cd atmos
```

### 2. Get API Key

Create a free account at:

https://www.weatherapi.com/

### 3. Configure API Key

Add your API key inside `WeatherService.js`:

```javascript
const API_KEY = "your_api_key_here";
```

### 4. Run the Application

Open `index.html` directly in your browser.

No backend server is required.


## Live Demo

https://alqamahansari.github.io/atmos/


## Learning Outcomes

Through this project, I explored:

- API integration workflows
- Modular JavaScript architecture
- Asynchronous data handling
- Geolocation-based services
- Responsive UI development
- Theme persistence using localStorage
- Frontend application structuring
- Weather data visualization


## Future Improvements

- Temperature unit conversion (°C / °F)
- Hourly forecast support
- Weather visualization charts
- Offline caching using service workers
- Dynamic weather-based backgrounds
- Backend proxy for API security
- Progressive Web App (PWA) support


## Security Note

API keys should not be exposed publicly in production applications.  
Environment variables or backend proxy approaches are recommended for secure deployments.


## Contributing

Pull requests, suggestions, and improvements are welcome.  
Feel free to fork the repository or open issues for enhancements.


## License

This project is licensed under the MIT License.


## Author

**Mohammad Alquamah Ansari**   
GitHub: https://github.com/alqamahansari  
Portfolio: https://alqamahansari.github.io/

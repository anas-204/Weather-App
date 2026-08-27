# 🌤️ Weather App

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.7-7952b3?logo=bootstrap&logoColor=white)

A beautiful, responsive weather application showing real-time weather data and 3-day forecasts.

[Live Demo](#) • [Report Bug](https://github.com/anas-204/Weather-App/issues) • [Request Feature](https://github.com/anas-204/Weather-App/discussions)

</div>

---

## ✨ Features

### Current Weather
- 🌡️ Real-time temperature and conditions
- 💨 Wind speed and direction
- 💧 Humidity percentage
- 🎨 Dynamic weather icons
- 📍 Location-based display

### Forecast
- 📅 3-day weather forecast
- 📊 Max/min temperatures
- 💧 Average humidity
- 💨 Wind speed predictions
- 🌅 Sunrise and sunset times
- 🌓 Day/night condition detection

### User Interface
- 📱 Fully responsive design
- 🎯 Search any location
- ⚡ Fast real-time updates
- 🎨 Modern card-based layout
- ✨ Clean and intuitive interface

### Additional Features
- 🌍 Global location support
- 📅 Date and day display
- 🧭 Wind direction indicators
- 💬 Newsletter subscription
- 🔗 Social media links

---

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling
- **JavaScript (ES6+)** - DOM manipulation & API calls
- **Bootstrap 5.3.7** - Responsive grid framework
- **Font Awesome 6.6.0** - Icons
- **Bootstrap Icons 1.11.3** - Additional icons
- **WeatherAPI.com** - Weather data API

---

## 📁 Project Structure

```
Weather-App/
├── index.html           # Main HTML file
├── Css/
│   ├── Style.css        # Custom styles
│   └── bootstrap.min.css # Bootstrap framework
├── Js/
│   ├── file,js          # Main JavaScript logic
│   └── bootstrap.bundle.min.js
└── images/              # Logo and icons
    ├── logo.png
    ├── banner.png
    ├── icon-wind.png
    ├── icon-umberella.png
    └── icon-compass.png
```

---

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/anas-204/Weather-App.git
cd Weather-App
```

2. **Open in browser**
```bash
# Simply open the index.html file in your browser
# Or use a local server
python -m http.server 8000
# Visit http://localhost:8000
```

---

## 📖 Usage

1. **Search for a location**
   - Enter a city name in the search box
   - Click the "Find" button

2. **View current weather**
   - Temperature and conditions
   - Wind speed and direction
   - Humidity percentage

3. **Check forecast**
   - 3-day weather prediction
   - Temperature ranges
   - Expected conditions

4. **Subscribe**
   - Enter email in footer to subscribe
   - Follow on social media

---

## 🌐 API

This app uses **WeatherAPI.com** for real-time weather data:
- Current weather endpoint
- Forecast API
- Astronomy API (sunrise/sunset)

```javascript
// Example API call
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=CITY_NAME
```

---

## 🎨 Features Breakdown

| Feature | Details |
|---------|---------|
| Current Weather | Live temperature, conditions, wind, humidity |
| 3-Day Forecast | Max/min temps, conditions, humidity, wind |
| Location Search | Find weather for any city worldwide |
| Day/Night Detection | Dynamic icons based on sunrise/sunset |
| Wind Direction | Cardinal and intercardinal directions |
| Responsive Design | Works on desktop, tablet, and mobile |

---

## 🔧 Configuration

To use your own API key:

1. Get an API key from [WeatherAPI.com](https://www.weatherapi.com)
2. Open `Js/file,js`
3. Replace the API key:
```javascript
var apiKey = "YOUR_API_KEY_HERE";
```

---

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

---

## 🐛 Troubleshooting

**API not working?**
- Check internet connection
- Verify API key is valid
- Ensure CORS is enabled in browser

**Weather icons not loading?**
- Check image file paths
- Verify API responses include icon URLs
- Clear browser cache

**Mobile display issues?**
- Check viewport meta tag
- Verify Bootstrap CSS is loaded
- Test in different browsers

---

## 🤝 Contributing

1. Fork the repository
2. Create feature branch: `git checkout -b feature/YourFeature`
3. Make changes and commit: `git commit -m 'Add feature'`
4. Push to branch: `git push origin feature/YourFeature`
5. Open Pull Request

---

## 📄 License

MIT License - see LICENSE file for details

---

## 💬 Support

- 📧 Email: [anas-204@github.com](mailto:anas-204@github.com)
- 🐛 Issues: [GitHub Issues](https://github.com/anas-204/Weather-App/issues)
- 💡 Discussions: [GitHub Discussions](https://github.com/anas-204/Weather-App/discussions)

---

## 🚀 Future Enhancements

- [ ] Multiple location tracking
- [ ] Weather alerts and warnings
- [ ] Hourly forecast
- [ ] Air quality index
- [ ] UV index display
- [ ] Weather maps integration
- [ ] Dark mode theme
- [ ] PWA support
- [ ] Local storage for favorites
- [ ] Weather notifications

---

## 📊 Current Weather Data

**Displayed Information:**
- Current temperature (°C)
- Weather condition with icon
- "Feels like" temperature
- Humidity level
- Wind speed (Km/h)
- Wind direction (N, S, E, W, etc.)
- Visibility
- Pressure

**Forecast Data:**
- Maximum temperature
- Minimum temperature
- Average humidity
- Wind speed
- Weather condition
- Sunrise/sunset times

---

<div align="center">

**Built with ❤️ for Weather Enthusiasts**

[GitHub](https://github.com/anas-204) | Maintained by [@anas-204](https://github.com/anas-204)

</div>

---

**Last Updated:** August 2024

---

## 🔗 Quick Links

| Resource | Link |
|----------|------|
| Repository | [GitHub](https://github.com/anas-204/Weather-App) |
| WeatherAPI | [weatherapi.com](https://www.weatherapi.com) |
| Bootstrap Docs | [getbootstrap.com](https://getbootstrap.com) |
| Font Awesome | [fontawesome.com](https://fontawesome.com) |

---

**© 2024 Weather App. All rights reserved.**

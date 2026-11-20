# Weather App Frontend 🌤️

This is the frontend for my Weather API project. It provides a clean, responsive user interface where users can search for any city and view real-time weather data.

## Live Demo
You can view the live application here: 
**[https://my-weather-app-ashen-two.vercel.app/](https://my-weather-app-ashen-two.vercel.app/)**

*(Note: The backend is hosted on Render's free tier, so if the app takes up to 50 seconds to load on the first search, it is just waking up the server.)*

## Features
- Search for weather by city name.
- Displays temperature, weather condition, and humidity.
- Responsive design that works on mobile and desktop.
- Handles error states gracefully (e.g., missing city, API wake-up delays).

## Tech Stack
- **HTML5 / CSS3**: For the layout and styling.
- **Vanilla JavaScript**: For DOM manipulation and making `fetch` requests to the backend API.
- **Vercel**: For hosting and continuous deployment.

## Backend API
This frontend connects to my custom Node.js/Express backend. 
Check out the backend repository here: [weather-api](https://github.com/Cantonia40/weather-api)

## How to run locally
1. Clone the repo.
2. Open `index.html` in your browser, or run a local server using `npx live-server`.

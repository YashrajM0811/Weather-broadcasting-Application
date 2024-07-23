# ReactJS Weather Broadcasting Application

Welcome to the ReactJS Weather Broadcasting Application! This project showcases the implementation of core React concepts to create a weather forecasting app using the OpenWeatherMap API. The application allows users to search for current weather information by city name.

## Introduction
This ReactJS Weather Broadcasting Application enables users to get real-time weather updates for any city. It leverages the OpenWeatherMap API to fetch weather data and displays it in a user-friendly interface.

## Features
- Search for current weather information by city name
- Displays temperature, weather conditions, and location
- Dynamic background changes based on temperature

## Screenshots
![Weather Broadcasting](/src/assets/image.png)

## Setup Instructions
To get started with this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/react-weather-broadcasting.git
   cd react-weather-broadcasting
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the app:**
   ```bash
   npm start
   ```

## Core Concepts
This project covers several core concepts of React, including:

- **State Management:** Using the `useState` hook to manage the state of the search query and weather data.
- **API Calls:** Fetching weather data from the OpenWeatherMap API.
- **Conditional Rendering:** Dynamically rendering content based on the state of the application.
- **Styling:** Applying conditional styling based on the temperature.

## Code Explanation

### Weather.js

The main component of the application, `Weather.js`, is responsible for rendering the weather information and handling user interactions.

#### API Configuration
The OpenWeatherMap API key and base URL.

- **State Management**
  Using `useState` to manage the state of the search query and weather data.

- **Event Handlers**
  Functions to handle changes in the search input and fetch weather data.

- **Date Builder**
  A utility function to format the date.

- **Rendering the Component**
  Returning the JSX that represents the weather app UI.


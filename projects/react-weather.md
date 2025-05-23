---
title: Climarselt
emoji: 🌦️
metaDescription: ClimArselt is a weather SPA built with React and TypeScript. With Data provided by OpenWeatherMap API via axios and state management with Zustand
date: 2025-05-20T13:00:00.000Z
summary: ClimArselt is a React-based web app built with typescript that displays real-time weather data 
tags:
  - React
  - TypeScript
  - Zustand
  - Tailwind
  - HTML
  - Design
  - Axios
  - Vite
  - Netlify Functions
---

**React Weather** is a web application that fetches weather data from the OpenWeather API. Built with React, TypeScript, and Vite, it provides real-time weather information, allowing users to search for weather by city name or coordinates.

## Live Demo
<a href="https://climarselt.netlify.app/" target="_blank" rel="noopener noreferrer">🚀 Deploy</a>
<a href="https://github.com/arselt/react-weather" target="_blank" rel="noopener noreferrer">📄 GitHub Repository</a>

![App UI thumbnail](https://github.com/arselt/react-weather/raw/main/thumbnail.png "UI Screenshot")

## Features
- Fetches and displays weather data from OpenWeather API
- Support for both metric and imperial units
- Current weather conditions display
- City-based and location-based weather search
- Responsive mobile first design
- Secure API key handling using Netlify Functions

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/arselt/react-weather.git
   cd react-weather
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Get an API key from [OpenWeather](https://openweathermap.org/api) and create a `.env` file in the project directory:
   ```sh
   VITE_API_KEY=your_openweather_api_key_here
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

## Deployment to Netlify

This project uses Netlify Functions to securely handle API requests without exposing your API key in the frontend code.

1. Fork or clone this repository to your GitHub account
2. Connect your repository to Netlify
3. Add the following environment variable in Netlify site settings:
   - Key: `OPENWEATHER_API_KEY`
   - Value: Your OpenWeather API key
4. Deploy the site

The project automatically uses the local API key during development and switches to Netlify Functions in production.

## Technologies Used
- React 19
- TypeScript
- Vite
- Axios for API requests
- Zustand for state management
- Tailwind CSS for styling
- React Loading Skeleton for loading states
- Netlify Functions for secure API handling

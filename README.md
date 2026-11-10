# NOXIS

### Weather, presented through a dynamic interface.

NOXIS is a city-based weather dashboard that transforms live weather data into a clear, visually driven interface. Built with HTML, CSS and vanilla JavaScript, it integrates WeatherAPI to retrieve current weather information and dynamically render relevant data and visual representations.

## Core Features

- **City-based Weather Search:** Retrieve current weather information for user-specified locations.
- **Dynamic Weather Dashboard:** Display temperature, humidity, wind speed and location information through dynamically updated UI elements.
- **Condition-Based Visualisation:** Map WeatherAPI condition codes to nine visual weather categories, allowing the interface to adapt its illustrations to changing weather conditions.
- **Interactive Search:** Support form-based searches through both button interaction and keyboard submission.
- **Error Handling:** Handle unsuccessful city searches and manage the visibility of weather and error interfaces.

## Technical Stack

| Technology | Application |
|---|---|
| HTML5 | Interface structure |
| CSS3 | Layout and visual presentation |
| JavaScript (ES6+) | Application logic and DOM manipulation |
| Fetch API | HTTP communication |
| WeatherAPI | Current weather data source |

## Engineering Highlights

The application uses asynchronous JavaScript to retrieve external API data, parses JSON responses, and updates the interface through DOM manipulation.

WeatherAPI condition codes are grouped into visual categories using JavaScript switch-case logic. This separates the API's detailed weather classifications from the application's visual representation.

The search workflow uses form event handling and prevents default browser submission behaviour, allowing weather data to be fetched without a page reload.

## Project Scope

NOXIS currently focuses on current weather retrieval through manual city search. Forecasting, automatic location detection and backend integration are outside the current implementation scope.

## Project Status

**Version 1.0 — Core weather functionality implemented.**

## Weather-Api

## Project Description
Weather Api is a simple browser-based weather application. Users can search for a city's current weather conditions, current UV-index, and five-day forecast. Previously searched cities can be quickly recalled from a search history list located below the input field.

Below is a link to my github repo,
https://github.com/Nowembabazi/Weather-Api

🌤️ A detailed light dashboard with a complete overview of live weather conditions in the specified city. Option to toggle weather data between Fahrenheit units. Sidebar with random major cities weather. Built using the OpenWeather API.

## Light Mode
<a href="https://github.com/Nowembabazi/Weather-Api" target="_blank"></a>



## Tech

- HTML5
- CSS3
- Bootstrap -4
- JavaScript
- OpenWeather API
- jQuery

## Key Features

**Design**

- Fully responsive without using any media queries
- Layout and responsive achieved using Bootstrap
- Styling done through custom CSS
- Light and dark mode themes using CSS variables
- Custom animated icons ([https://bas.dev/work/meteocons](https://bas.dev/work/meteocons))
- Custom loading spinner animation that will appear until all data has been downloaded
- Minimalistic and cohesive design
- Subtle shadow usage to increase contrast between certain text elements and icons
- Custom scrollbar styling

**Interactive Elements**

- Search cities from a database of over 200,000 cities with dynamic autosuggestions 
- Geolocation button fetches the user’s current location and updates all content based on user’s city
- Toggle weather data between imperial and metric
- ‘Forecast In Other Cities’ section shows current weather data for 5 random cities from around the world; clicking on the city will update the weather dashboard with that city’s weather data

## Future Features
-Responsive UI: The dashboard is designed to look sleek and simple across multiple breakpoints. On extra small devices, the application's search history collapses into a button allowing the user to toggle its visibility on and off.

-Dynamically Displayed Weather Data: The application does not need to be refreshed when requesting weather data for new cities. The user interface updates itself with each new request.

-UV Condition Indicator: Using the EPA's standards for UV conditions, the application renders the UV index in green when the condition is favorable, yellow when the condition is moderate, and red when the condition is severe.

-Intelligent Five-Day Forecast: Since five-day forecast data gets returned by the OpenWeather API in three-hour increments, the time coverage on the fifth day changes depending on when the request gets made. In order to maximize accuracy, the application looks to fill each of the five days using a noon forecast. If the application can't fulfill that goal for the fifth day, it uses a series of conditions to display the next best option.

## deployment 
A live vercel link
(https://weather-api-inky-ten.vercel.app/)

The project can also be run locally in Visual studio code using the live server.
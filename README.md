# MobileWeatherApp

Project written using the Ionic framework V3. 
The web app consists of the following pages:

Home Page - the first page of the application.The first time the application is run no city has yet been entered the so the News button and weather, and country data will be hidden.
Once a City has been saved persistently by the Settings page, weather and the first 5 news stories for the country the city is in are shown along with the country flag & country name
If the city name that has been saved in storage is not found an error message is displayed and no news or weather data shown.
If no news stories from the country are found an error message is displayed

Settings Page - allows the user of the app to enter a City for which weather data will be displayed. The default units are metric. If the user leaves the page without pressing the Save button, changes are not saved.
If the user presses Save but doesn’t enter a City he/she is presented with an error message.
When a City and Units have been successfully entered, the next time the Settings page is opened the city & units info is displayed.


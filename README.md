# Backend-API-for-weather-forecast
This is a simple Python Flask application that serves as an API to retrieve weather forecast data based on location. The application uses the OpenWeatherMap API for data retrieval.

Getting Started :

1)Clone the repository

2)Install the required dependencies :
Instructs the user to install the necessary Python packages using the pip install command.

3)Obtain an API key from OpenWeatherMap and replace API key with your actual API key.

4)Run the application:
The application will start, and you can access the weather information by sending a GET request on Postman to http://127.0.0.1:5000/weather with the 'location' parameter, like http://127.0.0.1:5000/weather?location=CityName.

API Endpoint :

Endpoint: /weather
Method: GET
Parameters:
location (required): The name of the city for which you want to retrieve the weather information.

Response :

The API responds with a JSON object containing weather information for the specified location. 

Error Handling :

If the 'location' parameter is missing, the API will respond with a 400 Bad Request and an error message.
If there is an issue with retrieving weather data from OpenWeatherMap, the API will respond with the appropriate HTTP status code and an error message.


![output screenshot](https://github.com/Somanathh/Backend-API-for-weather-forecast/assets/118989426/294f26a3-4e45-4c73-82ec-2e909cac0182)






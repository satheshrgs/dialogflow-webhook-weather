# weather_bot
Weather Bot using OWM deployed in dialogflow
# Dialogflow Webhook weather implementation in Python

This is a  simple webhook implementation that gets Dialogflow JSON request and returns a webhook fulfillment response.

More info about Dialogflow webhooks could be found here:
[Dialogflow Webhook](https://dialogflow.com/docs/fulfillment)

# Deploy to Heroku:
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# How to use?
* create a new agent in [Dialogflow](https://dialogflow.com/)
* Provide your fulfillment info. Deploy using heroku or provide your own. (https//www.example.com/webhook)
* Create the intent (like weather in singapore [$geo-city] ) and enable webhook fulfillment in the intent
* Test in your console
# Examples
#### weather in Avinashi
Today the weather in Avinashi:   
Temperature in Celsius:  
Max temp :29.0.  
Min Temp :29.0.  
Temperature in Fahrenheit:  
Max temp :84.2.  
Min Temp :84.2.  
Humidity :54.  
Wind Speed :2.6  
Latitude :11.19.  
Longitude :77.27  


# What does the service do?
It's a weather information fulfillment service that uses [Open Weather Map API](https://openweathermap.org/api).
The services takes the `geo-city` parameter from the action, performs geolocation for the city and requests weather information from Open Weather Map API 

The service packs the result in the Api.ai webhook-compatible response JSON and returns it to Api.ai.


## Terms
[Google APIs Terms of Service](https://developers.google.com/terms/).


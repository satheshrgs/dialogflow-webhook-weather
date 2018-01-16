# weather_bot
Weather Bot using OWM deployed in dialogflow
## Dialogflow Webhook weather implementation in Python
This service takes `geo-city` as a param from Dialogflow JSON request and find the weather for the provided city using Open Weather Map and returns a webhook response

More info about Dialogflow webhooks could be found here:
[Dialogflow Webhook](https://dialogflow.com/docs/fulfillment)

# Deploy to Heroku:
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# How to use?
* Create a new agent in [Dialogflow](https://dialogflow.com/)
* Provide your fulfillment info. Deploy using heroku or provide your own. (https//www.example.com/webhook)
* Provide API key of OWM as OWMApiKey with value in Config Vars of heroku (or) use your key directly in the file. 
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

### Terms
* [Google APIs Terms](https://developers.google.com/terms/).

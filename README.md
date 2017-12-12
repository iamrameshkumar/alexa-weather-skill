# Alexa Weather Skill

Alexa weather skill using OpenWeatherMap API.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites

This project requires **python3.5**

Create an account on http://openweathermap.org/api and get the **API KEY**.

Create *.env* file in project directory and complete it as below:

```
API_KEY=1234567890ABCDEFGH
CITY=London,UK
```

Obviously put your city there :)

Create *virtualenv* and install requirements.

```sh
virtualenv -p /usr/bin/python3.5 venv

source venv/bin/activate

pip install -r requirements.txt
```


### Configuration

Create an account on https://developer.amazon.com/

In developer console open **ALEXA** tab and click **Get Started** button below **Alexa Skills Kit** tab.

![alexa-weather-skill](https://i.imgur.com/7RkPiit.png)

Then click **Add a New Skill** button.

Complete **Name** and **Invocation Name** as follows:

![alexa-weather-skill](https://i.imgur.com/eKyJJ6V.png)

Click **Save**.

Complete Interaction model with intent schema and utterances. You will find them in project directory.

![alexa-weather-skill](https://i.imgur.com/MUqFAsN.png)

![alexa-weather-skill](https://i.imgur.com/xj5Inax.png)
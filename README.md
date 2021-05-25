Credit for boiler code: https://github.com/craigsdennis/intro-to-apis-flask  

This repository is meant to demonstrate the implementation of the twilio message API which allows the user to send SMS messages to verified numbers and retrieve message logs.

# Example Application - Complimentr

This application is meant to be used with the [Introduction to APIs course](https://github.com/craigsdennis/intro-to-apis-course).

## Local Installation

Copy `.env.example` to `.env` and update it with your [Twilio](https://twilio.com) credentials.

### Running the application

* `python -m venv .venv`
* `source ./.venv/bin/activate`
* `pip install -r requirements.txt`
* `FLASK_ENV=development flask run`

#### In Development mode

* Run [ngrok](https://ngrok.com/) on port 5000
* Visit your ngrok url!

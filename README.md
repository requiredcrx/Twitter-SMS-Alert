# Twitter-SMS-Alert
Here is a complete Python code that will send an SMS alert to your phone using Twilio when the Twitter account "@hacksultan" makes a new tweet: You can replace the twitter handle to get alert from other twitter account.

## Requirements
+ A [Twitter Developer account](https://developer.twitter.com/) and a new application to get access to the Twitter API
+ [tweepy,](https://github.com/tweepy/tweepy) a Python library for interacting with the Twitter API
+ A [Twilio account](https://www.twilio.com/) and a phone number to send SMS messages

## Setup
* Clone this repository and navigate to the project directory:
```
git clone https://github.com/YOUR_USERNAME/twitter-sms-alert.git
cd twitter-sms-alert
```
* Install the required libraries:
```
pip install -r requirements.txt
```
* Create a file called `secrets.py` and add your API keys and access tokens:
```
consumer_key = "YOUR_CONSUMER_KEY"
consumer_secret = "YOUR_CONSUMER_SECRET"
access_token = "YOUR_ACCESS_TOKEN"
access_token_secret = "YOUR_ACCESS_TOKEN_SECRET"
twilio_account_sid = "YOUR_TWILIO_ACCOUNT_SID"
twilio_auth_token = "YOUR_TWILIO_AUTH_TOKEN"
twilio_phone_number = "YOUR_TWILIO_PHONE_NUMBER"
```
* Run the script:
```
python main.py
```
## Configuration
You can customize the following parameters in the main.py file:

`TWITTER_HANDLE:` The Twitter handle of the account to monitor `(e.g. "hacksultan")`
`PHONE_NUMBER:` The phone number to send the SMS alerts to `(e.g. "+2349037080267")`

## License
This project is licensed under the MIT License - see the LICENSE file for details.


# fastapi-spam-detection
Deploying and Hosting an sklearn Spam Detection Model with FastAPI and Heroku

To test
```
curl -X 'GET' \
  'https://fast-dusk-61250.herokuapp.com/spam_detection_path/attention%3A%20claim%20your%20free%20prize%21' \
  -H 'accept: application/json'
```
You should get a similar response:
```
{"label":"spam","spam_probability":0.9999162619796017}
```

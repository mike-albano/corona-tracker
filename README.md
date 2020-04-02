# corona-tracker

Does an HTTP GET using Python Requests, plays a sound depending on result.

pip3 install -r requirements.txt

Usage example, for state of Colorado, country USA and county of Buolder:
```
python3 corona_tracker.py -s co -c usa -o boulder
```
Default is to perform the GET every hour; feel free to change the following to increase/decrease that:
```
API_INTERVAL
```

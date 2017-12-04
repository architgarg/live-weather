# live-weather
Takes address or pincode as string and returns weather of that location.

### Prerequisites

* NodeJS 


### Installing

```
npm install
```

* Copy and Paste .env.example as .env file

* Get a free API_KEY from forecast.io

* Open .env file and put 


```
API_KEY = your_api_key_here
```


### Examples


```
node app.js --address 110020
```

or

```
node app.js --address "new delhi"
```

or

```
node app.js -a "new delhi"
```


```
New Delhi, Delhi 110020, India
It's currently 70.54. It feels like 70.24.
```


## Built With

* [Google Maps](https://developers.google.com/maps/documentation/) - To fetch the lat, lang coordinates of the address.
* [DarkSky](https://darksky.net/dev) - To fetch weather of the address



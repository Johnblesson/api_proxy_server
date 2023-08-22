# api_proxy_server
A weather application with vanilla, node, express and api proxy server.

Server used for hiding API keys, rate limiting and caching. This uses the [OpenWeather API](https://openweathermap.org/api) but you can easily change it to whatever public API you are using

## Usage

### Install dependencies

```bash
npm init
npm install express 
npm install cors
npm install needle
npm install -D nodemon
```

### Run on http://localhost:5000

```bash
npm run dev
```

### Add public API info

Rename **.env.example** to **.env** and edit the values

If the public API URL is **https://api.openweathermap.org/data/2.5/weather?q={city}&appid={APIkey}**

- API_BASE_URL = "https://api.openweathermap.org/data/2.5/weather"
- API_KEY_NAME = "appid"
- API_KEY_VALUE = "YOUR API KEY"




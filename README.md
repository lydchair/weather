# weather

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Note:

1.
In order to change display Customized cities, days of showing, and to store Appid,.env.local file need to be add

Example: 

VUE_APP_NO_OF_DAYS=3

VUE_APP_WEATHER_APPID=

VUE_APP_CITIES=London,Tokyo,Melbourne,New York,Beijing

- After applied changes in .env.local file, you have to serve/build again to see the result.

2.
Since the forecast API gives 3 hours range for next 5 days, the forecast view is showing the same time range as the current time. For example: if current time is 7pm, forecast for next few days are shows the forecast of the range between 6-9pm og that day.


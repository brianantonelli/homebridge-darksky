# homebridge-darksky
Dark Sky API plugin for homebridge: https://github.com/nfarina/homebridge

This plugin will provide the current weather conditions via the Dark Sky API and provide temperature and humidity information for HomeKit. You can then display the values or use them for triggers. 

## Installation

1. Install homebridge using: `npm install -g homebridge`
2. Install this plugin using: `npm install -g homebridge-darksky`
3. Update your configuration file. See the sample below.

To finish up you'll need a developer key for Dark Sky which can you can create [here](https://darksky.net/dev/register). You'll also need your latitude and longitude, you can go to [Google Maps](https://www.google.com/maps) and click the "my location" button in the bottom right corner. the URL will update with your latitude and longitude. 

## Configuration

Configuration Sample:

```
"platforms": [
    {
        "platform": "MyWeather",
        "apiKey": "481njsdg293r23r...",
        "latitude": "33.9..",
        "longitude": "-84.3..
    }
]
```
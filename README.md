# WWeather

WWeather is a Waybar Weather module.

The script uses the Open-Meteo API, retrieving weather data based on the latitude and longitude of the selected city and province, and outputs the current temperature along with a weather condition icon.

Waybar config:
```
{
 "custom/weather": {
 "format": "{}",
 "exec": "~/.config/waybar/scripts/wweather.sh",
 "interval": 3600,
 "tooltip": false
 }
}
```
**The icons used are part of Font Awesome.**

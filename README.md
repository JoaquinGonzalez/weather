# Weather

Simple script to retrieve weather info from openweathermap.org API

## Usage
```
Weather
-a autoupdate
-u force update
-c print current temperature
-h print this message
```
## Configuration

Make sure to edit the file config.json with your data before installation
```
{
    "key": "<SET YOUR API KEY>",
    "lon": "<SET YOUR LONGITUDE>",
    "lat": "<SET YOUR LATITUDE>",
    "units": "<SET YOUR UNITS>"
}
```
## Installation
```
./configure
sudo make install
```
## Example
```
$ weather
Current: 12°C
Tomorrow (Min): 6°C
Tomorrow (Max): 15°C
```
```
$ weather -c
12°C
```

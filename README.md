# ForecastFit

Command-line Java app that recommends an outfit from the day's forecast.

Geocodes a typed location with OpenCage, pulls a daily forecast from Tomorrow.io, then maps temperature and precipitation to clothing.

## Run

```sh
export TOMORROW_API_KEY=...   # tomorrow.io
export OPENCAGE_API_KEY=...   # opencagedata.com
javac -cp lib/gson-2.10.1.jar ForecastFit.java
java -cp .:lib/gson-2.10.1.jar ForecastFit
```

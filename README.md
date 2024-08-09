# Files to be added to the project for it to run: 

First signUp for free acccount to access API.

 1 - https://rapidapi.com/wirefreethought/api/geodb-cities
 
 2 - https://openweathermap.org/api



#### Then, in folder /src/ - create "Api.js" with this :


```
export const geoApiOptions = {
	method: 'GET',
	headers: {
		'x-rapidapi-key': 'YOUR_API_KEY',
		'x-rapidapi-host': 'wft-geo-db.p.rapidapi.com'
	}
};

export const GEO_API_URL ="https://wft-geo-db.p.rapidapi.com/v1/geo";
export const WEATHER_API_URL = "https://api.openweathermap.org/data/2.5/";
export const WEATHER_API_KEY = "YOUR_API_KEY"

```

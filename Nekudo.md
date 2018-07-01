# Nekudo GeoIP
https://geoip.nekudo.com/  
Source: https://github.com/nekudo/shiny_geoip

# API Documentation
## Requests

All requests have to be HTTP GET requests in the following schema:  
  
http://geoip.nekudo.com/api/{ip}/{language}/{type}

## Parameters
**ip** 	*optional* 	Valid IP address in IPv4 or IPv6 format.  
**language** 	*optional* 	Two character language code like en or de.  
**type** 	*optional* 	Possible values are short to get a response conataining only most relevant data or full to get a response containing all available data.

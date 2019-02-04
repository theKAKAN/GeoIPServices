# IP Api
For Nekudo users
# API Documentation
# Requests
GET request to the following url:  
`https://ipapi.com/ip_api.php`
# Parameters
**ip** *required* The IP to be looked up

# No account?
The normal process requires one, but this one doesn't. And doesn't seem like it has a rate limit as well.

# Example
A GET request like this:  
```https://ipapi.com/ip_api.php?ip=72.229.28.185```  
returns:
```json
{
  "ip": "72.229.28.185",
  "hostname": "cpe-72-229-28-185.nyc.res.rr.com",
  "type": "ipv4",
  "continent_code": "NA",
  "continent_name": "North America",
  "country_code": "US",
  "country_name": "United States",
  "region_code": "NY",
  "region_name": "New York",
  "city": "New York",
  "zip": "10012",
  "latitude": 40.7255,
  "longitude": -73.9983,
  "location": {
    "geoname_id": 5128581,
    "capital": "Washington D.C.",
    "languages": [
      {
        "code": "en",
        "name": "English",
        "native": "English"
      }
    ],
    "country_flag": "http://assets.ipapi.com/flags/us.svg",
    "country_flag_emoji": "🇺🇸",
    "country_flag_emoji_unicode": "U+1F1FA U+1F1F8",
    "calling_code": "1",
    "is_eu": false
  },
  "time_zone": {
    "id": "America/New_York",
    "current_time": "2019-02-04T07:00:27-05:00",
    "gmt_offset": -18000,
    "code": "EST",
    "is_daylight_saving": false
  },
  "currency": {
    "code": "USD",
    "name": "US Dollar",
    "plural": "US dollars",
    "symbol": "$",
    "symbol_native": "$"
  },
  "connection": {
    "asn": 12271,
    "isp": "Charter Communications Inc"
  },
  "security": {
    "is_proxy": false,
    "proxy_type": null,
    "is_crawler": false,
    "crawler_name": null,
    "crawler_type": null,
    "is_tor": false,
    "threat_level": "low",
    "threat_types": null
  }
}
```

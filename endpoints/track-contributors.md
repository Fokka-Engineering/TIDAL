#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/tracks/38519997/contributors?countryCode=DE```
##### Optional Url Parameter
```limit=100``` (Item Limit)\
```offset=10``` (Item Offset)
##### Header
```authorization: Bearer {access_token}```or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
{
  "limit": 10,
  "offset": 0,
  "totalNumberOfItems": 0,
  "items": [
    {
      "name": "Acher Markus",
      "role": "Composer"
    },
    {
      "name": "Acher Michael",
      "role": "Composer"
    },
    {
      "name": "Abzocker Musikverlag",
      "role": "Music Publisher"
    }
  ]
}
```

#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/albums/38519994/credits?countryCode=DE```
##### Header
```authorization: Bearer {access_token}```or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
[
  {
    "type": "Design",
    "contributors": [
      {
        "name": "David Madson"
      }
    ]
  },
  {
    "type": "Primary Artist",
    "contributors": [
      {
        "name": "The Notwist",
        "id": 3529689
      }
    ]
  },
  {
    "type": "Record Label",
    "contributors": [
      {
        "name": "Alien Transistor"
      }
    ]
  }
]
```

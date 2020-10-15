#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/artists/4764457/videos?countryCode=DE&limit=2```
##### Optional Url Parameter
```limit=100``` (Item Limit)\
```offset=10``` (Item Offset)
##### Header
```authorization: Bearer {access_token}```or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
{
  "limit": 2,
  "offset": 0,
  "totalNumberOfItems": 24,
  "items": [
    {
      "id": 143147453,
      "title": "Atomised",
      "volumeNumber": 1,
      "trackNumber": 1,
      "releaseDate": "2020-06-16T00:00:00.000+0000",
      "imagePath": null,
      "imageId": "2ef62a00-e310-48ab-afc2-f8cb76757968",
      "duration": 263,
      "quality": "MP4_1080P",
      "streamReady": true,
      "streamStartDate": "2020-06-17T11:00:00.000+0000",
      "allowStreaming": true,
      "explicit": false,
      "popularity": 2,
      "type": "Music Video",
      "adsUrl": null,
      "adsPrePaywallOnly": true,
      "artist": {
        "id": 4764457,
        "name": "GoGo Penguin",
        "type": "MAIN"
      },
      "artists": [
        {
          "id": 4764457,
          "name": "GoGo Penguin",
          "type": "MAIN"
        }
      ],
      "album": null
    },
    {
      "id": 140633803,
      "title": "Don’t Go",
      "volumeNumber": 1,
      "trackNumber": 1,
      "releaseDate": "2020-05-14T00:00:00.000+0000",
      "imagePath": null,
      "imageId": "4a4ce91b-221a-4058-b437-452c91c07771",
      "duration": 171,
      "quality": "MP4_1080P",
      "streamReady": true,
      "streamStartDate": "2020-05-15T10:00:00.000+0000",
      "allowStreaming": true,
      "explicit": false,
      "popularity": 1,
      "type": "Music Video",
      "adsUrl": null,
      "adsPrePaywallOnly": true,
      "artist": {
        "id": 4764457,
        "name": "GoGo Penguin",
        "type": "MAIN"
      },
      "artists": [
        {
          "id": 4764457,
          "name": "GoGo Penguin",
          "type": "MAIN"
        }
      ],
      "album": null
    }
  ]
}
```

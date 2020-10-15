#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/artists/3529689/albums?countryCode=DE&limit=2```
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
  "totalNumberOfItems": 11,
  "items": [
    {
      "id": 64377395,
      "title": "Superheroes, Ghost-Villains + Stuff",
      "duration": 5948,
      "streamReady": true,
      "streamStartDate": "2016-10-14T00:00:00.000+0000",
      "allowStreaming": true,
      "premiumStreamingOnly": false,
      "numberOfTracks": 16,
      "numberOfVideos": 0,
      "numberOfVolumes": 1,
      "releaseDate": "2016-10-14",
      "copyright": "Alien Transistor",
      "type": "ALBUM",
      "version": null,
      "url": "http://www.tidal.com/album/64377395",
      "cover": "ba4e14ab-e110-41d9-8943-2efdf3c9367d",
      "videoCover": null,
      "explicit": false,
      "upc": "880918225265",
      "popularity": 14,
      "audioQuality": "LOSSLESS",
      "audioModes": [
        "STEREO"
      ],
      "artist": {
        "id": 3529689,
        "name": "The Notwist",
        "type": "MAIN"
      },
      "artists": [
        {
          "id": 3529689,
          "name": "The Notwist",
          "type": "MAIN"
        }
      ]
    },
    {
      "id": 38519994,
      "title": "Messier Objects",
      "duration": 3247,
      "streamReady": true,
      "streamStartDate": "2015-01-30T00:00:00.000+0000",
      "allowStreaming": true,
      "premiumStreamingOnly": false,
      "numberOfTracks": 17,
      "numberOfVideos": 0,
      "numberOfVolumes": 1,
      "releaseDate": "2015-02-03",
      "copyright": "Alien Transistor",
      "type": "ALBUM",
      "version": null,
      "url": "http://www.tidal.com/album/38519994",
      "cover": "44226420-6f7e-45d0-9dc6-197c4f4a5cb1",
      "videoCover": null,
      "explicit": false,
      "upc": "880918220925",
      "popularity": 19,
      "audioQuality": "LOSSLESS",
      "audioModes": [
        "STEREO"
      ],
      "artist": {
        "id": 3529689,
        "name": "The Notwist",
        "type": "MAIN"
      },
      "artists": [
        {
          "id": 3529689,
          "name": "The Notwist",
          "type": "MAIN"
        }
      ]
    }
  ]
}
```

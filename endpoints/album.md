
***
#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/albums/38519994/?countryCode=DE```
##### Header
```authorization: Bearer {access_token}``` or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
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
```

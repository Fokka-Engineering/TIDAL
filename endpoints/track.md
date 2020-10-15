#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/tracks/38519997/?countryCode=DE```
##### Header
```authorization: Bearer {access_token}```or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
{
  "id": 38519997,
  "title": "Object 3",
  "duration": 124,
  "replayGain": -4.25,
  "peak": 0.906234,
  "allowStreaming": true,
  "streamReady": true,
  "streamStartDate": "2015-01-30T00:00:00.000+0000",
  "premiumStreamingOnly": false,
  "trackNumber": 3,
  "volumeNumber": 1,
  "version": null,
  "popularity": 4,
  "copyright": "Alien Transistor",
  "url": "http://www.tidal.com/track/38519997",
  "isrc": "DEZ750500205",
  "editable": false,
  "explicit": false,
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
  ],
  "album": {
    "id": 38519994,
    "title": "Messier Objects",
    "cover": "44226420-6f7e-45d0-9dc6-197c4f4a5cb1",
    "videoCover": null
  },
  "mixes": {
    "TRACK_MIX": "001651ecb6f1c202a9ba7e2bbdab92"
  }
}
```

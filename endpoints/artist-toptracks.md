#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/artists/3529689/toptracks?countryCode=DE&limit=2```
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
  "totalNumberOfItems": 156,
  "items": [
    {
      "id": 82448461,
      "title": "Consequence",
      "duration": 313,
      "replayGain": -6.9,
      "peak": 1.0,
      "allowStreaming": true,
      "streamReady": true,
      "streamStartDate": "2017-12-05T00:00:00.000+0000",
      "premiumStreamingOnly": false,
      "trackNumber": 10,
      "volumeNumber": 1,
      "version": null,
      "popularity": 6,
      "copyright": "City Slang/big Store",
      "url": "http://www.tidal.com/track/82448461",
      "isrc": "DED620118410",
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
        "id": 82448449,
        "title": "Neon Golden",
        "cover": "ad3ed5f3-37a2-4b27-9002-b83459ab5a0e",
        "videoCover": null
      },
      "mixes": {
        "TRACK_MIX": "001981d70c53d5448599714c407079"
      }
    },
    {
      "id": 82448452,
      "title": "Pick up the Phone",
      "duration": 235,
      "replayGain": -7.53,
      "peak": 0.985626,
      "allowStreaming": true,
      "streamReady": true,
      "streamStartDate": "2017-12-05T00:00:00.000+0000",
      "premiumStreamingOnly": false,
      "trackNumber": 3,
      "volumeNumber": 1,
      "version": null,
      "popularity": 5,
      "copyright": "City Slang/big Store",
      "url": "http://www.tidal.com/track/82448452",
      "isrc": "DED620118403",
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
        "id": 82448449,
        "title": "Neon Golden",
        "cover": "ad3ed5f3-37a2-4b27-9002-b83459ab5a0e",
        "videoCover": null
      },
      "mixes": {
        "TRACK_MIX": "001b06c2307876ddd0a3f54dbd415a"
      }
    }
  ]
}
```

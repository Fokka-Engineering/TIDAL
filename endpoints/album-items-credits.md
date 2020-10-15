#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/albums/38519994/items/credits?countryCode=DE&limit=2```
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
  "totalNumberOfItems": 17,
  "items": [
    {
      "item": {
        "id": 38519995,
        "title": "Object 1",
        "duration": 111,
        "replayGain": -2.59,
        "peak": 0.911618,
        "allowStreaming": true,
        "streamReady": true,
        "streamStartDate": "2015-01-30T00:00:00.000+0000",
        "premiumStreamingOnly": false,
        "trackNumber": 1,
        "volumeNumber": 1,
        "version": null,
        "popularity": 5,
        "copyright": "Alien Transistor",
        "url": "http://www.tidal.com/track/38519995",
        "isrc": "DEZ750500203",
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
          "TRACK_MIX": "001734abc6480a525df5d3fc71ade1"
        }
      },
      "type": "track",
      "credits": [
        {
          "type": "Composer",
          "contributors": [
            {
              "name": "Acher Markus"
            },
            {
              "name": "Acher Michael"
            }
          ]
        },
        {
          "type": "Music Publisher",
          "contributors": [
            {
              "name": "Abzocker Musikverlag"
            }
          ]
        }
      ]
    },
    {
      "item": {
        "id": 38519996,
        "title": "Object 2",
        "duration": 116,
        "replayGain": 3.22,
        "peak": 0.980307,
        "allowStreaming": true,
        "streamReady": true,
        "streamStartDate": "2015-01-30T00:00:00.000+0000",
        "premiumStreamingOnly": false,
        "trackNumber": 2,
        "volumeNumber": 1,
        "version": null,
        "popularity": 1,
        "copyright": "Alien Transistor",
        "url": "http://www.tidal.com/track/38519996",
        "isrc": "DEZ750500204",
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
          "TRACK_MIX": "001dd1c1859bc7e6400e766180752a"
        }
      },
      "type": "track",
      "credits": [
        {
          "type": "Composer",
          "contributors": [
            {
              "name": "Acher Markus"
            },
            {
              "name": "Acher Michael"
            }
          ]
        },
        {
          "type": "Music Publisher",
          "contributors": [
            {
              "name": "Abzocker Musikverlag"
            }
          ]
        }
      ]
    }
  ]
}
```

#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/tracks/38519997/playbackinfoprepaywall?countryCode=DE&audioquality=LOSSLESS&playbackmode=STREAM&assetpresentation=PREVIEW```
##### audioQuality Enums
```LOW```(64kbps 22.05kHz MP3)
##### playbackmode Enums
```STREAM```
##### assetPresentation Enums
```PREVIEW```
##### Header
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
{
  "trackId": 38519997,
  "assetPresentation": "PREVIEW",
  "audioMode": "STEREO",
  "audioQuality": "LOW",
  "manifestMimeType": "application/vnd.tidal.bts",
  "manifest": "Base64 Encoded XML"
}
```
#### Definition
 + manifestMimeType: application/vnd.tidal.bts (DIRECT STREAM)
 + manifest (Base64 Encoded XML)

#### Example Decoded vnd.tidal.bts Manifest
``` yaml
{"mimeType":"audio/mpeg","codecs":"mp3","encryptionType":"NONE","urls":["https://ab-pr-fa.audio.tidal.com/something"]}
```
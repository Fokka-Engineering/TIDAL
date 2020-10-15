#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/tracks/38519997/streamUrl?countryCode=DE&soundQuality=LOSSLESS```
##### soundQuality Enums
```LOW```(96kbps AAC)\
```HIGH```(320kbps AAC)\
```LOSSLESS```(1411kbps|16bit/44.1kHz FLAC/ALAC)\
```HI_RES```(24bit/96kHz MQA encoded FLAC)

##### Header
```authorization: Bearer {access_token}```
#### Example Response

``` yaml
{
  "url": "http://sp-pr-fa.audio.tidal.com/mediatracks/something",
  "trackId": 38519997,
  "playTimeLeftInMinutes": -1,
  "soundQuality": "LOSSLESS",
  "encryptionKey": "",
  "codec": "FLAC"
}
```

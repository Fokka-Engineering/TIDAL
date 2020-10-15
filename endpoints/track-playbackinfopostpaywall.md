#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/tracks/38519997/playbackinfopostpaywall?countryCode=DE&audioquality=LOSSLESS&playbackmode=STREAM&assetpresentation=FULL```
##### audioQuality Enums
```LOW```(96kbps AAC)\
```HIGH```(320kbps AAC)\
```LOSSLESS```(1411kbps|16bit/44.1kHz FLAC/ALAC)\
```HI_RES```(24bit/96kHz MQA encoded FLAC)
##### playbackmode Enums
```STREAM```\
```OFFLINE```
##### assetPresentation Enums
```FULL```\
```PREVIEW```
##### Header
```authorization: Bearer {access_token}```
#### Example Response

``` yaml
{
  "trackId": 38519997,
  "assetPresentation": "FULL",
  "audioMode": "STEREO",
  "audioQuality": "LOSSLESS",
  "manifestMimeType": "application/vnd.tidal.bts",
  "manifest": "Base64 Encoded XML"
}
```
#### Definition
 + manifestMimeType: application/vnd.tidal.bts (DIRECT STREAM) | application/dash+xml (MPEG DASH)
 + manifest (Base64 Encoded XML)

#### Example Decoded vnd.tidal.bts Manifest
``` yaml
{"mimeType":"audio/flac","codecs":"flac","encryptionType":"NONE","urls":["http://sp-pr-fa.audio.tidal.com/mediatracks/something"]}
```
#### Example Decoded application/dash+xml Manifest
``` xml
<?xml version='1.0' encoding='UTF-8'?><MPD xmlns="urn:mpeg:dash:schema:mpd:2011" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:cenc="urn:mpeg:cenc:2013" xsi:schemaLocation="urn:mpeg:dash:schema:mpd:2011 DASH-MPD.xsd" profiles="urn:mpeg:dash:profile:isoff-main:2011" type="static" minBufferTime="PT2S" mediaPresentationDuration="PT124.073S"><Period id="0"><AdaptationSet id="0" mimeType="audio/mp4" subsegmentAlignment="true"><ContentProtection schemeIdUri="urn:mpeg:dash:mp4protection:2011" value="cenc" cenc:default_KID=""/><ContentProtection schemeIdUri="urn:uuid"><cenc:pssh></cenc:pssh></ContentProtection><ContentProtection schemeIdUri="urn:uuid:</cenc:pssh></ContentProtection><Representation id="0" codecs="flac" bandwidth="876379"><SegmentTemplate timescale="44100" initialization="https://sp-ad-fa.audio.tidal.com/mediatracks/something" media="https://sp-ad-fa.audio.tidal.com/mediatracks/something" startNumber="1"><SegmentTimeline><S d="176128" r="30"/><S d="11652"/></SegmentTimeline></SegmentTemplate></Representation></AdaptationSet></Period></MPD>
```
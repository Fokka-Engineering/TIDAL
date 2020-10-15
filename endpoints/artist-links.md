#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/artists/3529689/links?countryCode=DE```
##### Header
```authorization: Bearer {access_token}```or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
{
  "limit": 10,
  "offset": 0,
  "totalNumberOfItems": 8,
  "items": [
    {
      "url": "http://www.allmusic.com/artist/mn0000408427",
      "siteName": "ALLMUSIC"
    },
    {
      "url": "http://www.bbc.co.uk/music/artists/f180cec2-9421-4417-a841-c7372090d13d",
      "siteName": "BBC_MUSICPAGE"
    },
    {
      "url": "http://www.discogs.com/artist/Notwist%2C+The",
      "siteName": "DISCOGS"
    },
    {
      "url": "http://www.last.fm/music/The+Notwist",
      "siteName": "LAST_FM"
    },
    {
      "url": "http://decoda.com/the-notwist-lyrics",
      "siteName": "LYRICS"
    },
    {
      "url": "https://myspace.com/notwist",
      "siteName": "MYSPACE"
    },
    {
      "url": "http://www.notwist.com/",
      "siteName": "OFFICIAL_HOMEPAGE"
    },
    {
      "url": "http://de.wikipedia.org/wiki/The_Notwist",
      "siteName": "WIKIPEDIA"
    }
  ],
  "source": "MusicBrainz"
}
```

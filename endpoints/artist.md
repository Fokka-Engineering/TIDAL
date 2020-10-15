#### Example Request
##### Method
```GET```
##### Url
```https://api.tidal.com/v1/artists/3529689?countryCode=DE```
##### Header
```authorization: Bearer {access_token}```or\
```x-tidal-token: {client_id}``` (No Authentication Needed)
#### Example Response

``` yaml
{
  "id": 3529689,
  "name": "The Notwist",
  "artistTypes": [
    "ARTIST",
    "CONTRIBUTOR"
  ],
  "url": "http://www.tidal.com/artist/3529689",
  "picture": "2a4abc4a-faf5-4c06-b2a4-bf142459d894",
  "popularity": 36,
  "artistRoles": [
    {
      "categoryId": -1,
      "category": "Artist"
    },
    {
      "categoryId": 11,
      "category": "Performer"
    },
    {
      "categoryId": 1,
      "category": "Producer"
    },
    {
      "categoryId": 2,
      "category": "Songwriter"
    },
    {
      "categoryId": 3,
      "category": "Engineer"
    }
  ],
  "mixes": {
    "MASTER_ARTIST_MIX": "0157026712a3687e12af164ecb10ce",
    "ARTIST_MIX": "00008ded8a6682c338c2fbabd6619f"
  }
}
```

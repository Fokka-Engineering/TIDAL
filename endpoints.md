###### Artists

[```GET artists/{id}```][+](artist)

[```GET artists/{id}/bio```][+](artist-bio)

[```GET artists/{id}/links```][+](artist-links)

[```GET artists/{id}/mix```][+](artist-mix)

[```GET artists/{id}/toptracks```][+](artist-toptracks)

[```GET artists/{id}/videos```][+](artist-videos)

[```GET artists/{id}/albums```][+](artist-albums)
###### Albums

[```GET albums/{id}```][+]()

[```GET albums/{id}/credits```][+]()

[```GET albums/{id}/items```][+]()

[```GET albums/{id}/items/credits```][+]()

[```GET albums/{id}/review```][+]()
###### Playlists

[```POST playlists/{uuid}/items```][+]()

[```DELETE playlists/{uuid}```][+]()

[```DELETE playlists/{uuid}/items/{indices}```][+]()

[```GET playlists/{uuid}```][+]()

[```GET playlists/{uuid}/items```][+]()

[```GET playlists/{uuid}/recommendations/items```][+]()

[```POST playlists/{uuid}/items/{indices}```][+]()

[```POST playlists/{uuid}/items/{index}/replace```][+]()

[```POST playlists/{uuid}```][+]()
###### Tracks

[```GET tracks/{id}/contributors```][+]()

[```GET tracks/{id}/mix```][+]()

[```GET tracks/{id}/streamUrl```][+]()

[```GET tracks/{id}/playbackinfopostpaywall```][+]()

[```GET tracks/{id}/playbackinfoprepaywall```][+]()

[```GET tracks/{id}```][+]()
###### Videos

[```GET videos/{id}/contributors```][+]()

[```GET videos/{id}/streamUrl```][+]()

[```GET videos/{id}/playbackinfopostpaywall```][+]()

[```GET videos/{id}/playbackinfoprepaywall```][+]()

[```GET videos/{id}```][+]()
###### Mixes

[```GET mixes/{mixId}/items```][+]()
###### User
[```POST users/{userId}/facebook```][+]()

[```POST users/{userId}/favorites/albums```][+]()

[```POST users/{userId}/favorites/artists```][+]()

[```POST users/{userId}/favorites/playlists```][+]()

[```POST users/{userId}/favorites/tracks```][+]()

[```POST users/{userId}/favorites/videos```][+]()

[```POST users/{userId}/clients/{clientId}/offline/albums```][+]()

[```POST users/{userId}/clients/{clientId}/offline/playlists```][+]()

[```POST users/{userId}/playlists```][+]()

[```GET users/facebook/acceptedEULA```][+]()

[```GET users/{userId}/clients```][+]()

[```GET users/{userId}/favorites/ids```][+]()

[```GET users/{userId}/favorites/albums```][+]()

[```GET users/{userId}/favorites/artists```][+]()

[```GET users/{userId}/playlistsAndFavoritePlaylists```][+]()

[```GET users/{userId}/favorites/playlists```][+]()

[```GET users/{userId}/favorites/tracks```][+]()

[```GET users/{userId}/favorites/videos```][+]()

[```GET users/{userId}/handovertoken```][+]()

[```GET users/{userId}/clients/{clientId}/offline/albums```][+]()

[```GET users/{userId}/clients/{clientId}/offline/playlists```][+]()

[```DELETE users/{userId}/clients/{clientId}/offline/all```][+]()

[```DELETE users/{userId}/facebook```][+]()

[```DELETE users/{userId}/favorites/albums/{albumId}```][+]()

[```DELETE users/{userId}/favorites/artists/{artistId}```][+]()

[```DELETE users/{userId}/favorites/playlists/{uuid}```][+]()

[```DELETE users/{userId}/favorites/tracks/{trackId}```][+]()

[```DELETE users/{userId}/favorites/videos/{videoId}```][+]()

[```DELETE playlist/{uuid}```][+]()

[```DELETE users/{userId}/clients/{clientId}/offline/albums/{albumId}```][+]()

[```DELETE users/{userId}/clients/{clientId}/offline/playlists/{playlistUuid}```][+]()

[```POST users/{userId}/subscription/updateWithAmazon```][+]()

[```POST users/{userId}/image```][+]()
###### Pages
[```GET pages/home```][+]()

[```GET pages/explore```][+]()

[```GET pages/videos```][+]()

[```GET pages/mix```][+]()

[```GET pages/my_collection_my_mixes```][+]()
###### Search
[```GET search/albums```][+]()

[```GET search/artists```][+]()

[```GET search/playlists```][+]()

[```GET search```][+]()

[```GET search/tracks```][+]()

[```GET search/videos```][+]()
###### Widevine

[```POST drm/licenses/widevine```][+]()

[```POST streamingprivileges/tokens```][+]()

###### Authentication
[```POST oauth2/token```][+]()

[```POST oauth2/device_authorization```][+]()

[```GET users/{userId}/loginToken```][+]()

[```GET username/password```][+]()

###### Miscellaneous
[```GET country```][+]()

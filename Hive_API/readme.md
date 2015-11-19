#Hive Project
Hive is a collaborative way to play music. Plug a host phone into your speakers and all of your friends can send music to the hive to play.
## Planned Features
* Push songs from any phone with Hive to a host phone connected to speakers
* Location aware notifications ("You are near the *[name of hive]*. Tap to join")
* Allow for simple voting for next songs to play off hive host (useful for bars/nightclubs wanting to make their music experience interactive)
## How it works
* Hive will run in the backend on Microsoft Azure as a cloud API providing RESTful access to the client apps
* Client apps will be able to push music and music requests to the API
* The API will push these requests to the corresponding host app
* The host app will execute these requests.
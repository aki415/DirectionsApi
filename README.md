# DirectionsApi
Hi Sir, This is to explain some of the work i did in this old repositary which was for the final group.
For starters, since i was part of the maps and api team we had to use api keys which contained necessary information such as the Android SDK for Google Maps,Directions,Places,Distance Matrix and other api keys
which were all combined into one api key. The api key you see in the project is mine and i researched and combined all these api keys into the one.
I highlighted before some parts i did in the main Mapsactivity.kt file which includes sections such as importing some libraries,defining certain geographical locations from the apis, 
working on parts of the oncreate,creating the onmapready function where the function gets called when the GoogleMap instance is ready. In this function, markers are placed on the map at locations A click listener is set for the markers which, 
when activated, fetches the route between these two locations, draws or removes a polyline for this route on the map, and calculates and displays the distance between these points. If there's an issue in fetching the directions, an error message is displayed. 
Also, the map's camera is set to focus on Trinity College with a specific zoom level. I created the onResponse function which  gets called when the application receives a response from an HTTP 
request made using the OkHttp library. I also worked on parts of the search loction section.
I also created the getDiretions function which sponsible for making a request to the Google Directions API to obtain directions between two locations and uses the OkHttp library.
Other functions I created also include the decodepoly function which decodes an encoded polyline 
string and return a list of LatLng objects representing the decode path, a draw poly line function which visually displayed these routes on the map for the user.
I had to carefully create the functions that parse the JSON responses and ensure all the data was appropriately stored and displayed in the app.
I also worked in the resources folder such as adding interactive buttons and displaying distance in km to name a few.

# LIRI-BOT (a Language Interpretation and Recognition Interface)

LIRI is a command line node app that takes in parameters and gives you back data based off the following parameters: 

-	concert-this
-	Spotify-this-song
-	movie-this
-	do-what-it-says


## concert-this: 

This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

-	Name of the venue
-	Venue location
-	Date of the Event (use moment to format this as "MM/DD/YYYY")

##Spotify-this-song: 

This will show the following information about the song in your terminal/bash window

-	Artist(s)
-	The song's name
-	A preview link of the song from Spotify
-	The album that the song is from

##movie-this: 

This will output the following information to your terminal/bash window:
-	Title of the movie.
-	Year the movie came out.
-	IMDB Rating of the movie.
-	Rotten Tomatoes Rating of the movie.
-	Country where the movie was produced.
-	Language of the movie.
-	Plot of the movie.
-	Actors in the movie.

##do-what-it-says: 

LIRI will use the text from “random.txt” and call on of LIRI’s commands. 
It should run Spotify-this-song for “I want it That way”. 

## Development 

We wanted to create a personal drone portfolio/platform for drone enthusiast to share their work, upload content and tag it with a location. In knowing the location, users are also able to access the weather to determine if it is appropriate to fly.  


## Technologies used:

* Spotify API
* OMDB API
* Bands In Town API
* Node.js
* Javascript
* NPM packages



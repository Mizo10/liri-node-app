# liri-node-app

# Overview
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface.
LIRI is a command line node app that takes in a user's input/request and provides the user with the data he/she requested back in the CLI.

# Liri's Commands
Please use one of the following commands to interact with the application (NOTE carefully, commands are case sensitive):

concertThis  
spotifyThis
moviethis
do-what-it-says

# What Each Commands Can Do
1. `node liri.js concertThis <artist/band name here>`

     * Name of the venue
     * Venue location
     * Date of the Event ("MM/DD/YYYY")
     Inline-style: 
!(https://i.ibb.co/p1Mmfz4/concert-This.png)

2. `node liri.js spotifyThis '<song name here>'`

     * The song's name
     * Artist(s)
     * The album that the song is from
     * A preview link of the song from Spotify
     Inline-style: 
!(https://i.ibb.co/sP139c5/spotify-This.png)
     
     *If no song is provided then your program will default to "The Sign"*

3. `node liri.js movieThis '<movie name here>'`

     * Title of the movie.
     * Year the movie came out.
     * IMDB Rating of the movie.
     * Rotten Tomatoes Rating of the movie.
     * Country where the movie was produced.
     * Language of the movie.
     * Plot of the movie.
     * Actors in the movie.
     Inline-style: 
!(https://i.ibb.co/0sy2zzh/movie-This.png)
     
      
4. `node liri.js do-what-it-says`
Inline-style: 
!(https://i.ibb.co/4F5SqLg/do-what-it-says.png)

   
   
# Technologies Used

* JavaScript
* Node.js
* BandsInTown API (via Axios npm module)
* Spotify API (via Stopify npm module)
* OMDB API (via Axios npm module)

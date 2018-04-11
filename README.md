# liri-node-app

LIRI is a _Language_ Interpretation and Recognition Interface

The purpose of this program is to give users the ability to look up information in regards to certain songs and movies and also look back on past tweets. 

It comes with a list of commands that users can enter before the name of a movie or song and then return back information.

node liri.js my-tweets
This will show your last 20 tweets and when they were created at in your terminal/bash window.

node liri.js spotify-this-song "song title"
This will show the following information about the song in your terminal/bash window
     
     * Artist(s)
     
     * The song's name
     
     * A preview link of the song from Spotify
     
     * The album that the song is from

If no song is provided then your program will default to "The Sign" by Ace of Base.


node liri.js movie-this "movie title" 
This will output the following information to your terminal/bash window:

     ```
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.

node liri.js do-what-it-says
Using the `fs` Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.
     
Node Package Modules used in this program:
Twitter
Spotify
Request
DotEnv
FS

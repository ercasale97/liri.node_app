# liri.node_app
Built with
Node Axios
Dotenv
Bands in Town API
OMBD API
Node Spotify API

Getting Started

In this assignment, I created a LIRI application, a language interpretation and recognition interface app that runs on the command line. LIRI takes in parameters from clients, and sends back a response. The data returns comes from OMBD, Bands in Town, and Spotify.

LIRI can be started by accessing the terminal, and entering commands. To begin, first clone my GitHub repository for this application, and run npm install. You must also create a .env file, as well as provide your own API keys for the external sites listed above. 

How to Use

To search for data within LIRI, enter one of the following node commands: concert-this, spotify-this-song, movie-this, and do-what-it says. These commands will make an API call related to your search string.

Movie-this searches the OMBD API to retrieve the movie title, release year, rating, location, language, and actors. Running this command without entering in movie information will default to information for the movie Mr. Nobody.

(images/movie-this.png)
(images/movie-this-default.png)


Concert-this function searches the Bands in Town API to retrieve information the client put into the command line. It will log information of the artist searched, info regarding the upcoming concert, venue, location, and date.

Spotify-this searches the Spotify API to retrieve artist name, song name, album, and a preview link.

Do-what-it-says uses the fs node package to use text in random.txt, and use it to call application commands and functions. Running do-what-it-says will run spotify-this-song for “I Want it That Way.”

GitHub Repository
https://github.com/ercasale97/liri.node_app


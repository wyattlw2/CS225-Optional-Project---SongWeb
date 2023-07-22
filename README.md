# SongWeb

This project uses Spotify's API to measure popularity-similarity overlap between songs in any playlist on Spotify. Each retrieved song has two measures; one is a popularity index indicating how often the song is played, and the other is a set of genre labels that describe the song. A graph with weighted edges is constructed from the retrieved songs, telling which song nodes have the highest outward degree (corresponding to its number of unique genres) and which two songs have the highest shared edge weight (corresponding to the two most popular songs that share a genre). Data retrieval was done in Python using the spotipy library. The project is interacted with using a CLI.

Commit history may not have been carried over so to state solely my contributions, I coded:

* Unweighted BFS Algorithm

* Betweenness Centrality Algorithm

* Roughly half of the test cases, mostly for the stuff I wrote

* Minor contributions to Graph data structure

Everything else was designed by others(*) and for those I receive no credit. More info is available in the project folder, which contains a full write-up that was used for project submission purposes.

(*)The file_to_V2D function was a function made for in-class assignments that was used due to its immediate availability for parsing data.

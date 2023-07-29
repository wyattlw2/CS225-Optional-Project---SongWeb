# SongWeb

This project uses Spotify's API to measure popularity-similarity overlap between songs in any playlist on Spotify. Each retrieved song has two measures; one is a popularity index indicating how often the song is played, and the other is a set of genre labels that describe the song. A graph with weighted edges is constructed from the retrieved songs, telling which song nodes have the highest outward degree (corresponding to its number of unique genres) and which two songs have the highest shared edge weight (corresponding to the two most popular songs that share a genre). Data retrieval was done in Python using the spotipy library. The project is interacted with using a CLI.

Commit history may not have been carried over so to state solely my contributions, I worked on:

* BFS

* Betweenness Centrality

* Roughly half of the test cases, mostly for the stuff I wrote

* Graph class


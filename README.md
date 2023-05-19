# Automation-of-Playlist-Creation
This model creates automatic playlists based on our previous musical history.

# Introduction
In today's digital era, music streaming platforms like Spotify offer vast libraries of songs, making it challenging for users to manually create and curate personalized playlists. Personalized playlists play a crucial role in enhancing the music listening experience by catering to individual preferences, moods, and musical tastes. To address this challenge, there is a need for automated methods that can efficiently organize large music libraries and generate tailored playlists.

# Objective
The objective of this research is to automate the process of playlist creation on Spotify by leveraging high-dimensional data and CLustering algorithms.

# Methodology:
## Data collection: Extraction of audio feature data from the Spotify API for songs in a given playlist.
## Feature selection: Identifying relevant audio features such as popularity, liveness, loudness, speechiness, tempo, and valence.
## Preprocessing: Normalization and scaling of feature data to ensure comparability.
## K-means clustering: Applying the K-means algorithm to group songs into clusters based on their feature similarities.
## Playlist generation: Assigning songs to clusters and creating smaller playlists within each cluster.

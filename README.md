# Spotify-EDA-2023

## Objective Purpose :

* Analyzing the dataset about "Most Streamed Song in 2023 on Spotify Platform"
* How the most popular song on Spotify Platformn 2020 until 2023
* The preference of music features from people that make a song to listen and be popular song
* The Relationship between chart and playlist on Spotify Platform

## Understanding the Data
* I'm using the Kaggel dataset 'spotify-2023.csv' with file size 103.8 Kb with tittle " Most Streamed Spotify Songs 2023".
* It has 953 observations and 24 columns : Track_name, artist(s)_name, artist_count, released_year, released_month, released_day, in_spotify_playlists,in_spotify_charts, streams, in_apple_playlists, in_apple_charts, in_deezer_playlists, in_deezer_charts, in_shazam_charts, bpm, key, mode, danceability_%, valence_%, energy_%, acousticness_%, instrumentalness_%, liveness_%, speechiness_%. This Dataset provides the most streamed on Spotify start from 1987 until 2023.
* For the more information, may be seen here : https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023

## Analysis Result 

1. The Most Popular Song Streamed on Spotify Platform Between 2020 untill 2023
   ![image](https://github.com/riizd30/Spotify-EDA-2023/assets/150936052/75626d13-21ad-4cc8-b4b4-aa51f5cd1b80)
2. Total Stream By Released_year from 2020 Untill 2023
   ![image](https://github.com/riizd30/Spotify-EDA-2023/assets/150936052/5966ee79-a12c-4a85-a611-a39b68cec1b0)
3. The Correlation between Stream, Spotify Playlist and Spotify Charts
   ![image](https://github.com/riizd30/Spotify-EDA-2023/assets/150936052/ffbb3c2c-f343-4e8c-bf23-f82876d77472)

The insights for correlations :
   * The correlation between "streams" and "in_spotify_playlists" is 0.837, indicating a strong positive correlation. This implies that songs with higher streaming numbers are likely to be included more frequently in Spotify playlists.
   * The correlation between "streams" and "in_spotify_charts" is 0.765, indicating a strong positive correlation. This implies that songs with higher streaming numbers are also likely to perform well in the overall Spotify charts.
4. linear regression model fit about Streams and Spotify Charts
   ![image](https://github.com/riizd30/Spotify-EDA-2023/assets/150936052/3ab0033b-8274-415a-97f6-d9516d128e1d)

**Positive Trend** :
If the regression line has a positive slope, A positive slope for the regression line indicates a positive connection between "streams" and "in_spotify_charts." This implies that there is a tendency for the presence on Spotify charts to increase with the number of streams.

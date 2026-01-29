# playlist_analysis
A deep dive into music playlists from a leading streaming service.

## Notebooks

Planning to do 4 bits of work with this dataset, starting with unsupervised exploration, and then going deeper into track order and membership. Culminating with some insight, stats or models that can be used to help generate good playlists, with the potential to be popular.


1. Latent rock genre analysis - exploring the different clusters of rock playlists

**TO DO:**

2. Playlist flow comparison - highlight and identify which playlists flow better in terms of e.g. tempo
3. Hit track association model - should track X be a part of playlist Y?
4. Create better rock playlists


## Data overview


As well as the playlist level information (how many followers does a playlist have, what tracks and order), there is a large set of data on tracks, artists and audio features.

## Track level information
### Describing artists, popularity, streams etc.,


![Alt text](assets/sel_12d_combined_stream_count_by_popularity_linear.png)





## Audio feature information
### Specific features derived from the audio such as key, tempo etc.. as well as estimates on danceability, instrumentalness etc..


![Alt text](assets/sel_af_23c_feature_heatmap_grid.png)


![Alt text](assets/sel_af_25_mode_by_key.png)


## Artist level information
### Primarily interested in genres - genres are given on a per artist level, some artists have more than on genre. With over 700 genres there is a lot of nuance here.

![Alt text](assets/sel_02_top_genres.png)

![Alt text](assets/sel_04_genre_sunburst.png)







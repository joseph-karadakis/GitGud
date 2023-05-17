# GitGud
UCI- DATA ANALYTICS - Project 1 / Group 2
Raw Data Source: https://www.kaggle.com/datasets/dhruvildave/spotify-charts
API Documentation: https://developer.spotify.com/documentation/web-api
Limitations: 2017 - 2022 only from Spotify

Process:

1.Used spotify_data_raw to filter and clean data and output into Spotify_USA_Top10_raw.csv
2.Used Spotify_Top10_clean to further trim down the dataset by humanizing values like key, mode, danceability etc and output into Spotify_USA_Top10_clean.csv
3.Used Spotify_Top10_Analysis for calculations of correlation factors and visualization of data. Every chart was exported as .png in the Output folder
4.Continued data analysis trying to figure out the combination of attributes that would predict popularity in a new song 
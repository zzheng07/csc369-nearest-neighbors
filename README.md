# csc369-nearest-neighbors

This project is about understanding and practiceing fundamental distributed computing practices. We choose Spotiy playlist as our dataset and work collaboratively on the dataset on Databricks. The goals we've achieved

+ Gather dataset from public resource
+ Set up Spark Environment in Databricks
+ Analyze Spotify playlist datasets to determine sentiment with textblob
+ Compare Apache Spark’s approach to a Naive, non-distributed approach
+ Determine the correlation between the aggregated sentiment score of track names and the playlist name

1. [Development Environment](./development_environment.md)
2. Dataset Sample
   + `mpd_slice_0_999.json`
   + `mpd.slice.22000-22999.json`
3. [Presentation](CSC369_Group_8_Final_Presentation.pdf)
4. [Spotify Sentiments Notbook](Spotify_Sentiments.ipynb)

### Tools

+ [Textblob](https://textblob.readthedocs.io/en/dev/) -  sentiment analysis
+ [NLTK Data](https://www.nltk.org/nltk_data/) - Natural Language Toolkit used by Textblob
+ [Databricks Spark](https://databricks.com/) - Community Edition of Spark Cluster
+ [Spotify Million Playlist Dataset Challenge](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)
    - Participation Required to get the dataset

### Note

Our notebook is developed on DataBricks Spark cluster. All the dataset are uploaded to the cluster and managed by the DataBricks. To run the notebook locally, you may need to change the path to the dataset files and initialization of Spark first

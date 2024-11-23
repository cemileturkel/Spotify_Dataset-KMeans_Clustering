# KMeans Clustering Analysis

This repository contains data and code for performing KMeans clustering analysis on a Spotify_Dataset.csv. The primary dataset used in this analysis is `Spotify_Dataset.csv`.

## Dataset

The `Spotify_Dataset.csv` file contains the following columns:

- **title**: The title of the song.
- **artist**: The artist of the song.
- **top genre**: The specific genre of the song.
- **genre simplified**: A simplified genre classification.
- **year**: The release year of the song.
- **bpm**: Beats per minute of the song.
- **energy**: Energy level of the song.
- **danceability**: Danceability score of the song.
- **dB**: Loudness of the song in decibels.
- **liveness**: Liveness score of the song.
- **valence**: Positivity score of the song.
- **duration**: Duration of the song in seconds.
- **acousticness**: Acousticness score of the song.
- **speechiness**: Speechiness score of the song.
- **popularity**: Popularity score of the song.
- **Cluster**: The cluster label assigned to each song after clustering.

## Analysis

The analysis includes the following steps:

1. **Data Loading and Preparation**:
   - Load the dataset using pandas.
   - Select relevant features for clustering.

2. **KMeans Clustering**:
   - Apply KMeans clustering with the optimal number of clusters.
   - Add the cluster labels to the dataset.

## Usage

To run the analysis, follow these steps:

1. Clone the repository: ```bash
   git clone https://github.com/cemileturkel/Spotify_Dataset-KMeans_Clustering.git
   cd Spotify_Dataset-KMeans_Clustering
   
Install the required dependencies:

pip install -r requirements.txt
Run the analysis script:

python analysis.py

Results
The results of the analysis, including visualizations and clustering performance metrics, are saved in the results directory.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

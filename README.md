# Anime Recommendation System

## Overview

This project implements an anime recommendation system using collaborative filtering and data analysis techniques. It utilizes datasets from [MyAnimeList](https://myanimelist.net/) containing anime information and user ratings to provide personalized recommendations.

## Installation

To run this project, you will need to clone the repository and get the [file](https://github.com/Xernnn/Anime-Recommendation/Anime_Recommendation.ipynb) and the datasets to Google Colabs

```bash
git clone https://github.com/Xernnn/Anime-Recommendation.git
cd Anime_Recommendation
```

## Usage

1. Mount your Google Drive to access the datasets:
```bash
from google.colab import drive
drive.mount("/content/gdrive")
```

2. Load the datasets:

```bash
import pandas as pd
movies_df = pd.read_csv('/content/gdrive/My Drive/path/to/anime.csv')
ratings_df = pd.read_csv('/content/gdrive/My Drive/path/to/rating_complete.csv')
```

3. Run the analysis and recommendation

## Datasets

- **anime.csv**: Contains information about various anime titles including names, genres, and ratings from MyAnimeList (until 2021)
- **rating_complete.csv**: Contains anonymous user ratings for different anime, which is used to generate recommendations.

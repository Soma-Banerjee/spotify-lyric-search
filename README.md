# Spotify Lyric Search

## Overview
This project implements a text-identification system that predicts the **song title** and **artist name** when given a small snippet of lyrics. The solution is designed using Natural Language Processing (NLP) techniques and similarity-based matching.

## Dataset
The dataset contains the following columns:
- artist
- song
- link
- text (lyrics)

Only the `artist`, `song`, and `text` columns are used for model training and prediction.


Due to GitHub file size limitations, the dataset is not included in this repository.

Dataset Source:
(https://www.kaggle.com/datasets/joebeachcapital/57651-spotify-songs)

After downloading, place the CSV file inside the `data/` folder:


## Technologies Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Text preprocessing (lowercasing, punctuation removal)
2. Feature extraction using TF-IDF Vectorization
3. Similarity computation using Cosine Similarity
4. Prediction of the most relevant song and artist based on lyric similarity

# Accuracy
This model uses TF-IDF vectorization combined with cosine similarity to match a lyric snippet with the most relevant song lyrics. Performance is evaluated by testing multiple lyric snippets and observing correct song and artist identification.

## Installation & Execution

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/spotify-lyric-search.git
cd spotify-lyric-search



# CODE_ALPHA_MUSIC-RECOMMDATION-SYSTEM
In this experiment, a music recommendation system was developed using Natural Language Processing (NLP) and machine learning techniques. The system recommends songs based on the textual analysis of song lyrics.
Data Loading & Cleaning: Loaded a dataset of song lyrics and metadata, handled missing values, and selected a random sample of 5000 songs.
Text Preprocessing: Converted lyrics to lowercase, removed special characters, and applied tokenization and stemming.
Feature Extraction: Used TF-IDF vectorization to convert lyrics into numerical vectors.
Similarity Calculation: Computed cosine similarity between the vectors to measure song similarity.
Recommendation Logic: Developed a function to recommend the top 10 most similar songs based on a given song.

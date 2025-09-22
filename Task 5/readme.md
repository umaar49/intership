# 🎬 Content-Based Movie Recommendation System

This project is a content-based recommendation system that suggests movies similar to a user’s choice. The system uses movie metadata such as genres, keywords, cast, crew, and overviews to find related movies.

Unlike collaborative filtering (which requires user ratings), this approach relies only on the content of the movies themselves.

## 🚀 Features

Extracts useful information like genres, keywords, cast, crew, and overview from the dataset.

Creates a new feature called tags by combining all important information.

Uses text preprocessing (tokenization, lowercasing, lemmatization).

Converts text into vectors using:

Sentence Transformers (for semantic embeddings and better accuracy).

Calculates similarity between movies using cosine similarity.

Provides a function to recommend the top 5 similar movies for any given movie.

## 📂 Dataset

The project uses the TMDB 5000 Movies and Credits dataset, which can be found on Kaggle:
👉 TMDB 5000 Movie Dataset

Files used:

tmdb_5000_movies.csv

tmdb_5000_credits.csv

## 🛠 Technologies Used

Python

Pandas, NumPy – Data handling and cleaning

SpaCy – Text preprocessing

scikit-learn – cosine similarity

Sentence Transformers – Semantic embeddings (for improved recommendations)

## 📌 How It Works

Data Cleaning – Extract genres, keywords, cast, crew, and process them into lists.

Feature Engineering – Combine everything into one feature called tags.

Text Processing – Lowercase, remove spaces, and lemmatize words.

## Vectorization

Sentence Transformers: Converts tags into semantic embeddings that understand meaning.

Similarity Calculation – Cosine similarity is used to measure closeness between movies.

Recommendation Function – Given a movie name, the system finds and displays the top 5 most similar movies.

## 📊 Example Results

Input: Avatar
Output Recommendations:

Serenity

Jupiter Ascending

The Inhabited Island

Star Trek Into Darkness

Final Fantasy: The Spirits Within

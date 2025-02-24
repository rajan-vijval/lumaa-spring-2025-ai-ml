# Movie Recommendation System

## Overview

This project implements a  recommendation system using TF-IDF Vectorization and Cosine Similarity. It provides users with the top 5 movie recommendations based  on the similarity of movie plot summaries to a given query.

The dataset utilized for this project is the CMU Plot Summaries dataset, which contains 42,306 movie plot summaries extracted from Wikipedia and metadata extracted from Freebase, downloaded from [Movie Personas Dataset](http://www.cs.cmu.edu/~ark/personas/).

## Solution

### Data Loading and Preprocessing:

Loaded data and identified ID columns (Wikipedia ID). Renamed columns for consistency across datasets. 

### Text Vectorization (TF-IDF):

Applied TF-IDF (Term Frequency-Inverse Document Frequency) to convert plot summaries into numerical vectors, capturing important words in each summary.

### Similarity Calculation (Cosine Similarity):

Computed cosine similarity scores between the user query and movie plot vectors.

### Recommendation Generation:

Ranked movies by cosine similarity to user query.

Returned top 5 movies most relevant to the user's query.

## Other
### Files

Lumaa Solution.ipynb: Full implementation with user input in last cell
requirements.txt: 2 libraries I used for this solution
Solution Video.mp4: Screen share of running the notebook on my personal laptop
\data: Datasets from CMU Repository.

### Usage

Simply run the notebook Lumaa Solution.ipynb, enter a query describing the type of movie plot you're interested in, and the system will generate and display the top movie recommendations based on your input.

### Results

The solution effectively demonstrates how basic natural language processing (NLP) techniques can be applied to build an intuitive recommendation system without requiring explicit user ratings or complex metadata.

### Future Enhancements

Incorporate embeddings for better understanding of relationships between words. Use genre and character tropes to enhance recommendations. 

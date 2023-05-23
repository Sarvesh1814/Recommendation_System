# Recommendation System - Google Local Reviews (2018)

This project focuses on building a recommendation system for local places based on user reviews from the Google Local Reviews dataset (2018). The dataset contains reviews provided by local users for various local places.

## Dataset

The dataset used for this project is the Google Local Reviews dataset from 2018. It includes user reviews and ratings for different local places. The dataset provides valuable insights into user preferences and opinions about local establishments.

## Implemented Recommendation Systems

This project implements two types of recommendation systems:

1. Content-Based Recommendation System (from Scratch):
   - The content-based recommendation system leverages the textual content of the reviews to recommend similar places to users.
   - The system uses techniques like TF-IDF (Term Frequency-Inverse Document Frequency) to represent the reviews as feature vectors.
   - Cosine similarity is employed to measure the similarity between user preferences and place features.
   - Based on the similarity scores, the system recommends places that are likely to be of interest to the users.

2. Multi-round Recommendation System (from Scratch):
   - The multi-round recommendation system takes into account both user preferences and place features.
   - Word2Vec embeddings are created for the user-feature and place-feature matrices to capture the semantic relationships between users, features, and places.
   - The system employs collaborative filtering techniques to recommend places based on the preferences of similar users.
   - It utilizes the learned embeddings to improve the accuracy and relevance of the recommendations.

## Word2Vec Embeddings

Word2Vec embeddings are created for the user-feature and place-feature matrices. These embeddings capture the semantic relationships between users, features, and places based on the patterns observed in the reviews. The embeddings help in understanding the context and similarity between different entities, enabling more accurate recommendations.

## Technologies Used

The following technologies and libraries are used in this project:

- Python: The primary programming language for implementing the recommendation systems and data processing.
- NumPy: A fundamental library for numerical computing in Python, providing support for large, multi-dimensional arrays and matrices.
- Pandas: A powerful library for data manipulation and analysis, used for handling and preprocessing the dataset.
- Scikit-learn: A comprehensive machine learning library for Python, providing various tools for data preprocessing and similarity calculations.
- Gensim: A library for natural language processing, used for creating Word2Vec embeddings.
- Matplotlib: A plotting library for creating visualizations to analyze and present the results.

## Getting Started

To get started with this project, follow these steps:

1. Download the Google Local Reviews dataset (2018) from the appropriate source or obtain it from the project owner.

2. Install the required dependencies and libraries mentioned above using the appropriate commands or by setting up a virtual environment.

3. Preprocess the dataset to extract relevant features and perform any necessary data cleaning or transformation.

4. Implement the content-based recommendation system from scratch, considering the TF-IDF representation and cosine similarity.

5. Implement the multi-round recommendation system from scratch, utilizing Word2Vec embeddings and collaborative filtering techniques.

6. Evaluate the performance of the recommendation systems using appropriate metrics such as precision, recall, or mean average precision.

7. Visualize and analyze the results to gain insights into the effectiveness of the recommendation systems.

Please refer to the project's code files and documentation for more detailed instructions on running and utilizing the recommendation systems.

## Future Enhancements

Here are some potential areas for future enhancements:

- Incorporate more advanced natural language processing techniques for text preprocessing, such as stemming, lemmatization, or sentiment analysis, to improve the quality of textual features.



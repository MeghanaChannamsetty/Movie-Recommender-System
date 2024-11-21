# Movie Recommender System
This project is a Content-Based Movie Recommendation System that recommends movies based on the similarity of their content. The recommendation system was developed using Python, machine learning, and natural language processing techniques. The recommendations include both the movie titles and their posters, fetched via the TMDb API.
**Framework Used:**
  1. Streamlit: To build an interactive web application.
**Libraries Used:**
  1. Numpy
  2. Pandas
  3. Natural Language ToolKit(NLTK)
  4. Scikit Learn
  5. pickle
**Modules and Submodules Used:**
  1. nltk.stem.porter
  2. sklearn.feature_extraction.text
  3. sklearn.metrics.pairwise
**Algorithms Used:**
  1. Porter Stemmer
  2. CountVectorizer
  3. cosine_similarity

**At first, two datasets were taken from Kaggle and then preprocessed. The preprocessing steps included:**
1. Removing null values to ensure data integrity.
2. Merging the two datasets on a common column, id, to combine the relevant information.
3. Dropping unnecessary columns to focus on relevant features for the recommendation system.

**Key Algorithms and Techniques Used**:
1. PorterStemmer Algorithm (nltk.porter.stem):
This algorithm is used to perform stemming, which removes suffixes from words (e.g., "running" becomes "run"). This helps to avoid variations of the same word and ensures better matching in the recommendation system.

**CountVectorizer Algorithm (sklearn.feature_extraction.text):**
The CountVectorizer converts a collection of text documents into a matrix of token counts. It helps transform the textual data into numerical form, enabling comparison between different movies based on their content.

**Cosine Similarity (sklearn.metrics.pairwise):**
This algorithm calculates the cosine distance between two vectors. In this case, it measures the similarity between movies based on their content features. The higher the cosine similarity, the more relevant the recommended movie is to the selected one.

Used Streamlit Framework to build an web page



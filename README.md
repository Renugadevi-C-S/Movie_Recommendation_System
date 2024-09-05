                                                 MOVIE RECOMMENDATION SYSTEM
A simple content-based movie recommendation system that employs TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity to suggest movies based on movie titles. It searches for similar movies by comparing features such as genres, keywords, taglines, cast, and director.

                    Features
1. Suggests movies similar to a given movie based on multiple features.
2. Text data is processed using TF-IDF vectorization.
3. Uses Cosine Similarity to compute similarity scores between movies.
4. Handles missing data gracefully by filling them with empty strings.
5. Provides a list of the top 10 most similar movies.

                     Technologies Used
 **Python:** The core programming language for the project.
 
 **Pandas:** For handling and processing the movie dataset.
 
 **scikit-learn (sklearn):** For implementing the TF-IDF vectorizer and cosine similarity.
 
 **difflib:** For finding close matches to the user's input movie title.

                        How It works
**Input:** The user provides their favorite movie title.

**Find Closest Match:** The system searches for the closest match to the movie title provided using difflib.

**TF-IDF Transformation:** The system combines selected features (genres, keywords, tagline, cast, and director) and transforms the data into a TF-IDF matrix.

**Cosine Similarity:** It calculates the cosine similarity between the provided movie and all other movies in the dataset.

**Movie Recommendation:** It sorts the movies by similarity and suggests the top 10 most similar movies.

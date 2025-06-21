# Recommendation-System-Engine-for-Movies
# Movie Recommendation System

This project is a **Content-Based Movie Recommendation System** built using Python. It suggests movies similar to a user’s favorite based on genre similarity using **TF-IDF vectorization** and **cosine similarity**.

## Files Included
- Movie Recommendation System.ipynb — Main Jupyter Notebook containing all code.
- movies.csv — Dataset file with movie information (title, genre, etc.).

##  How It Works
1. **Load and Preprocess Data**:
   - Read the dataset using pandas.
   - Handle missing values.

2. **Convert Genre Text to Vectors**:
   - Use TfidfVectorizer from sklearn to convert genres into numerical vectors.

3. **Calculate Similarity**:
   - Compute cosine similarity scores between all movie vectors.

4. **User Input & Matching**:
   - Accept a movie name from the user.
   - Use difflib to find the closest match in the dataset.

5. **Recommendation**:
   - Rank and display the top 10 most similar movies based on similarity score.

##  Example Output

Enter your favourite movie name : iron man
Movies suggested for you :
1. Iron Man 2
2. Iron Man 3
3. Avengers: Age of Ultron
...

## Libraries Used
- pandas
- sklearn
- difflib



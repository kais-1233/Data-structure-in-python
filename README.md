🎬 Movie Recommendation System
A simple content-based movie recommendation system that suggests 5 similar movies using TF-IDF vectorization and cosine similarity.

📌 Project Description
This project recommends movies based on their content (like genres, overview, and keywords). When a user selects a movie, the system analyzes its features and returns the top 5 most similar movies.

🧠 Methodology
Content-Based Filtering:
Vectorizes movie overviews and metadata using TF-IDF
Calculates similarity using cosine similarity
Returns the top 5 similar movies to the selected one
📂 Dataset
Source: Kaggle - TMDB 5000 Movie Dataset
Key columns used: title, overview, genres, keywords, cast, crew
🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
NLTK or spaCy (optional for text preprocessing)
Streamlit (optional for web app UI)
✅ Output
The system displays 5 recommended movies based on the content similarity of the selected movie.

📸 Example
User inputs: Avatar
Output:
Aliens vs Predator: Requiem Aliens Falcon Rising Independence Day Titan A.E.

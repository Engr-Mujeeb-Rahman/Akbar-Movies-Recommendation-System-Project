# Akbar Movies Recommendation System 🎥

Welcome to the **Akbar Movies Recommendation System**! This application leverages **Machine Learning** to provide personalized movie recommendations. With a user-friendly interface and insightful suggestions, it's your gateway to discovering amazing movies.

---

## 🌟 Features
- **ML-Driven Recommendations**: Uses a precomputed similarity matrix to suggest movies based on your input.
- **Top 5 Movies Displayed**: Shows five highly relevant movies tailored to your choice.
- **Dynamic Posters**: Fetches movie posters via **The Movie Database (TMDb) API**.
- **Interactive Design**: Built with **Streamlit**, ensuring a seamless and engaging user experience.

---

## 🚀 Technologies Used
- **Python**: Core programming language.
- **Streamlit**: Framework for creating interactive web applications.
- **Pandas**: For data manipulation and processing.
- **Pickle**: For storing precomputed data and similarity matrices.
- **TMDb API**: For fetching movie posters dynamically.

---

## 🔧 How It Works
1. The user selects a movie from the dropdown menu.
2. The app calculates the similarity scores using a precomputed similarity matrix.
3. Displays five recommended movies with their posters.
4. Each recommendation includes captions like "Top Pick," "Highly Recommended," and "Fan Favorite."

---

## 📂 Project Structure
```
.
├── app.py                     # Main application code
├── movies.pkl                 # Preprocessed movie dataset
├── similarity_matrix.pkl      # Precomputed similarity matrix
├── logo_movies.png            # Sidebar logo image
├── img.jpg                    # Header or other decorative image
├── background.jpg             # Background image
└── requirements.txt           # List of dependencies
```

---

## 🔑 API Key
This application uses the TMDb API to fetch movie posters. Make sure to replace the placeholder API key in the code:
```python
api_key = "your_tmdb_api_key"
```

### Made with ❤️ by **Mujeeb Akbar**

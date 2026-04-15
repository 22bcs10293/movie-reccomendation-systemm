🎬 Movie Recommender System

A Movie Recommendation System built using Python and Streamlit.
This application recommends movies similar to a selected movie using a content-based filtering approach.

🚀 How to Use

Visit the Live App:
👉 https://movie-reccomendation-systemmgit-kexg2jqffigesdogshkkxy.streamlit.app/

Select a movie from the dropdown list.

Click the “Recommend” button.

Instantly view the recommended movies displayed on the screen.

📌 Project Overview

The Movie Recommender System helps users discover new movies by analyzing movie content such as:

Genres

Keywords

Cast

Director

Overview

Based on these features, the system finds movies that are most similar and recommends them to the user.

✨ Key Features

User-friendly web interface built with Streamlit

Content-based movie recommendations

Fast similarity computation using Cosine Similarity

Movie posters and ratings fetched using TMDB API

Efficient recommendation model using preprocessed data

🧠 Recommendation Technique

This project uses Content-Based Filtering, which recommends movies based on similarities between movie attributes rather than user behavior.

Steps Involved:

Data preprocessing using TMDB 5000 Movies dataset

Feature extraction and tag generation

Text vectorization using CountVectorizer

Similarity calculation using Cosine Similarity

Displaying top recommended movies

🛠️ Technologies Used
Technology	Description
Python	Core programming language
Streamlit	Web application framework
Pandas	Data manipulation
Scikit-learn	Vectorization & similarity
Requests	API handling
TMDB Dataset	Movie data source
🚀 How to Run the Project

Activate virtual environment:

venv\Scripts\activate


Run the application:

streamlit run app.py


Open browser and go to:

http://localhost:8505

📂 Project Structure
Movie-Recommendation-System/
│
├── app.py                 # Main Streamlit application
├── data.csv               # Processed movie dataset
├── movie_recommender.ipynb# Data preprocessing notebook
├── requirements.txt       # Required dependencies
├── LICENSE                # MIT License
└── README.md              # Project documentation

👤 Author

Bhumika Wadhwa
📧 Email: bhumikawadhwa12b01@gmail.com

🧾 License

This project is licensed under the MIT License.

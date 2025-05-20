BOOK RECOMMENDATION SYSTEM:
  The Book Recommender System is a web-based application built with Python (Flask) and HTML/CSS (Bootstrap) that helps users discover books based on their interests. It uses collaborative filtering and a precomputed similarity matrix to suggest books similar to a user-provided input.

FEATURES:
  Homepage showcasing the Top 50 most popular books with:
  Book title
  Author name
  Average rating
  Number of votes
  Book cover image

RECOMMENDATION PAGE WHERE USERS CAN:
  Enter the name of a book they like
  Receive 5 similar book recommendations instantly
  View book cover, title, and author of each recommended book

TECH STACK:
  Frontend: HTML, CSS (Bootstrap)
  Backend: Flask (Python)
  Data Handling: Pandas, NumPy, Pickle for model loading
  Machine Learning: Collaborative filtering using cosine similarity

FILES AND DEPENDENCIES:
  app.py: Main Flask application
  templates/: Contains HTML templates for the homepage and recommendation page
  pop.pkl, pt.pkl, books.pkl, similarity_score.pkl: Preprocessed data and model files

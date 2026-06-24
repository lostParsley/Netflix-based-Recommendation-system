# 🎬 Netflix based Movie Recommendation System

A content-based movie recommendation platform that helps users discover movies similar to their interests. The application combines machine learning, natural language processing, sentiment analysis, and real-time movie metadata retrieval to deliver personalized movie suggestions.

## Features

* Intelligent movie recommendations using content-based filtering
* Sentiment analysis of movie reviews using NLP
* Real-time movie details fetched from TMDB API
* Movie posters, ratings, genres, runtime, and cast information
* Interactive and responsive user interface
* Fast recommendation generation with pre-trained machine learning models

## Tech Stack

### Backend

* Python
* Flask
* Scikit-Learn
* Pandas
* NumPy
* NLTK

### Data Processing

* Feature Engineering
* Text Vectorization
* Content-Based Filtering
* Sentiment Analysis

### APIs & Scraping

* TMDB API
* BeautifulSoup4
* Requests

### Deployment

* Flask
* Gunicorn
* GitHub

---

## Project Architecture

1. Data Collection and Cleaning
2. Feature Engineering
3. Movie Similarity Computation
4. Recommendation Engine Development
5. Review Sentiment Classification
6. Flask Application Development
7. Deployment and Testing

---

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python main.py
```

Open:

```text
http://127.0.0.1:5000
```

---

## Dataset

The recommendation engine utilizes movie metadata including:

* Title
* Genre
* Overview
* Keywords
* Cast
* Crew Information
* Ratings

These features are transformed into vector representations and used to calculate movie similarity scores.

---

## Key Learning Outcomes

* Recommendation System Design
* Natural Language Processing
* Machine Learning Model Deployment
* REST API Integration
* End-to-End ML Application Development

---

## Future Improvements

* User Authentication
* Personalized User Profiles
* Watchlist Functionality
* Hybrid Recommendation Engine
* Collaborative Filtering
* Movie Trailer Integration
* Cloud Deployment

---

## Author

**Abhash Singh**

Software Engineering | Machine Learning | Data-Driven Systems

* Finalist - Smart India Hackathon 2025
* Competitive Programmer
* Full Stack & AI Enthusiast

---

## License

This project is intended for educational and portfolio purposes.

# Movie Recommendation System - Analyzing Similar Movie Names

## Overview
A Python-based system that recommends movies by analyzing and comparing movie name similarities using text matching algorithms.

## Features
- Name-based similarity matching
- Text analysis using NLP techniques
- Fuzzy matching for typo tolerance
- Similarity scoring and ranking
- Quick search functionality

## Technology Stack
- Python 3.x
- Pandas, NumPy
- scikit-learn (TF-IDF, Cosine Similarity)
- NLTK/difflib (Text matching)
- Streamlit (UI)

## Installation

```bash
git clone https://github.com/Ropriya/Movie-recommendation-analyzing-similar-movie-name-python.git
cd Movie-recommendation-analyzing-similar-movie-name-python
pip install -r requirements.txt
python app.py
```

## Usage

```python
Input: "The Dark Knight"
Output:
- The Dark Knight Rises (95% match)
- Batman: The Dark Knight Returns (88% match)
- Knight and Day (65% match)
```

## How It Works
1. Preprocesses movie names (lowercase, remove special characters)
2. Calculates similarity using Levenshtein Distance, TF-IDF, and Cosine Similarity
3. Ranks movies by similarity score
4. Returns top N matches

## File Structure
```
Movie-recommendation-analyzing-similar-movie-name-python/
├── app.py
├── requirements.txt
├── movie_analyzer.py
├── data/
│   └── movies.csv
└── README.md
```

## Author
**Rohit Ranjan**
- GitHub: [github.com/Ropriya](https://github.com/Ropriya)
- LinkedIn: [linkedin.com/in/contact-rohit-ranjan](https://linkedin.com/in/contact-rohit-ranjan)

---

*Find movies with similar names instantly!* 🎬🔍
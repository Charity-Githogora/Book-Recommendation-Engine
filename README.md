📚 Book Recommendation Engine using K-Nearest Neighbors (KNN)

This is a content-based recommendation system that suggests similar books based on user ratings patterns.


Technical Implementation

Built With
- Python 3
- Pandas (Data processing)
- Scikit-learn (KNN algorithm)
- SciPy (Sparse matrices)

Dataset
Used the Book-Crossings dataset containing:
- 1.1 million ratings (scale 1-10)
- 270,000 books
- 90,000 users

Key Steps
1. Data Filtering:
   - Kept only users with ≥200 ratings
   - Kept only books with ≥100 ratings
2. Rating Matrix:
   - Created user-book matrix using pivot tables
   - Converted to sparse matrix for efficiency
3. KNN Model:
   - Used cosine similarity metric
   - Implemented brute-force algorithm
4. Recommendation Logic:
   - Finds 5 nearest neighbors
   - Returns sorted by similarity score

Project Achievements
- Successfully passed all freeCodeCamp test cases
- Implemented proper data preprocessing for statistical significance
- Achieved accurate recommendations with similarity scoring

Installation & Usage
1. Clone repo:
   bash
   git clone https://github.com/Charity-Githogora/Book-Recommendation-Engine
   ```
2. Install requirements:
   ```bash
   pip install pandas scikit-learn scipy
   ```
3. Run Jupyter notebook:
   ```bash
   jupyter notebook book_recommendation.ipynb
   ```

Algorithm Insights
- Uses 'cosine similarity' to measure book similarity based on user ratings patterns
- 'KNN algorithm' finds books with closest rating patterns
- 'Sparse matrix' optimization handles large dataset efficiently


License
MIT License - free for academic and commercial use

---

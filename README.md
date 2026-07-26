# Music_Popularity_Predictor

A machine learning project that predicts whether a Spotify song is likely to be popular based on its audio features.

The project uses Support Vector Machine (SVM) to classify songs using a popularity threshold of 60.

# About the Dataset
The dataset contains 32,833 Spotify tracks with information about songs, artists, playlists, and audio characteristics.

The cleaned dataset was obtained from Kaggle's fe-course-data dataset.

# Features Used
The model uses features such as:

Loudness
Tempo
Speechiness
Acousticness
Instrumentalness
Liveness
Valence
Duration
Key
Mode

A song is classified as:
Popular: popularity score ≥ 60
Not Popular: popularity score < 60

# Model
I used Support Vector Classification (SVC) with:
RBF kernel
Polynomial kernel
StandardScaler for feature scaling

# Results
The model achieved approximately 72% accuracy.

However, further evaluation showed that the model struggled to correctly identify popular songs. This highlighted the importance of looking beyond accuracy and considering metrics such as precision, recall, F1-score, and the confusion matrix.

# Tools
Python | Pandas | NumPy | Seaborn | Matplotlib | Scikit-learn | Jupyter/Google Colab

# Future Improvements
Address class imbalance
Tune model parameters
Test other machine learning algorithms
Improve prediction of popular songs

Project focus: Exploring how machine learning can be applied to Spotify data to predict music popularity

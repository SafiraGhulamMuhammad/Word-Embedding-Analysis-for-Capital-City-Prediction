# Word-Embedding-Analysis-for-Capital-City-Prediction

This project focuses on utilizing pre-trained word embedding vectors to predict capital cities of countries. The main goal is to leverage cosine similarity and Euclidean distance metrics to assess the similarity between word vectors and make accurate predictions.

**Key Features:**

- **Cosine Similarity and Euclidean Distance Functions:** Implemented functions to calculate cosine similarity and Euclidean distance between word embedding vectors. These functions are essential for measuring the similarity between word vectors.

- **Capital City Prediction:** Developed a function that takes three input words along with the embeddings dictionary and predicts the capital city of a country. By leveraging cosine similarity and Euclidean distance, the function accurately predicts the country corresponding to a given set of words.

- **Accuracy Assessment:** After predicting the capital cities, the model's accuracy is evaluated by comparing the predicted countries with the actual capital cities stored in a dataframe. This evaluation step ensures the reliability and effectiveness of the prediction model.

- **Principal Component Analysis (PCA):** Implemented PCA to reduce the dimensionality of word embedding vectors from 300 dimensions to 2 dimensions. This step is crucial for visualizing word embeddings in a 2D space, allowing for easier interpretation and analysis.

- **Data Preprocessing:** The project includes data preprocessing steps such as mean normalization, computing covariance matrices, and obtaining eigenvectors and eigenvalues. These steps are essential for performing PCA and transforming word vectors into lower-dimensional space.

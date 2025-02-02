## 🎶 **Music Genre Classification using K-Nearest Neighbors (KNN)**
This project uses K-Nearest Neighbors (KNN) to classify music genres, leveraging the GTZAN Dataset from Kaggle. The goal is to explore the effectiveness of KNN in genre classification using extracted audio features.

### Project Overview
Music genre classification is a task that categorizes audio samples into predefined genres. This project uses KNN, a simple yet powerful instance-based learning algorithm, to classify tracks based on feature vectors derived from audio data.

### 📁 Dataset

The project uses the GTZAN Dataset from [Kaggle](https://kaggle.com), which includes:-

+ Genres: Blues, Classical, Country, Disco, Hip-hop, Jazz, Metal, Pop, Reggae, and Rock.
+ Audio files: 1,000 .wav files (100 files per genre).
+ File format: 30-second .wav files.
+ Music Genre Classification using K-Nearest Neighbors (KNN)

Link to the dataset on Kaggle : [GTZAN music genre classification dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

### 🎛️ Features Extraction
Using the Librosa library, we extract several key features from each audio file:

Model performance is evaluated based on accuracy and confusion matrix.

### 📊 Results
After training and testing, the KNN model achieves an accuracy of approximately X% (adjust based on your results) on the GTZAN dataset. The confusion matrix reveals performance across different genres, highlighting any specific challenges in classification.

### 🤝 Acknowledgments
This project is based on the GTZAN Dataset hosted on Kaggle, Special thanks to the contributors for making this dataset available for research and experimentation.



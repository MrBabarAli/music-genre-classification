### Music Genre Classification using Audio Features and CNN ###
This project presents a dual-model system for automatic music genre classification using both tabular audio features and image-based spectrograms. It uses the well-known GTZAN dataset to train two separate models:
📊 Tabular Model: Uses numerical features extracted from audio (like MFCC, Chroma, Spectral Contrast).

🖼️ CNN Model: Classifies genres based on visual spectrogram representations of audio clips.

The project aims to compare the performance of classical ML approaches (e.g., Random Forest, Logistic Regression) with deep learning CNNs on image data for the same classification task.

🔍 Objectives
Explore and process the GTZAN dataset (CSV + Spectrogram Images)

Train tabular models using scikit-learn

Train image-based CNN models using TensorFlow/Keras

Build a simple web interface using Flask (Python) and Streamlit (Jupyter-compatible)

Compare performance between models based on:

Accuracy

Precision / Recall

F1-score

Inference speed

Model size

🧠 Models Used
1. Tabular Classification
Logistic Regression

Random Forest

Decision Tree

2. Image Classification
Convolutional Neural Network (CNN)

Input: Spectrogram images

Output: Genre label (e.g., rock, classical, jazz, etc.)


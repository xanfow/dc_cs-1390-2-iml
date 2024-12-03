# Music Genre Classification + Recommendation Project by Divyam Chaudhary
This is Divyam Chaudhary's (1020221520) final project for Introduction to Machine Learning (CS-1390/PHY-1390-2) with Prof. Sandeep Juneja on the thesis: Music Genre Classification and Content-Based Recommendation System.

## Project Report
[add link]

## Overview
Traditional music recommendation systems rely heavily on collaborative filtering, which suggests music based on the listening behavior of other users with similar tastes. While this method can be effective, it often fails to consider the actual audio characteristics of songs, potentially limiting the diversity and accuracy of the recommendations. With this project, I aim to develop a machine learning model (a CNN in particular) to classify music based on genre and build a recommendation system that suggests songs to users based on similarities in the songs they listen to. I aim to improve recommendation accuracy by focusing on content-based similarities such as rhythm, mood, harmony, associated emotions, etc. These features are aptly captured in the MFCCs (mel-frequency cepstral coefficients) of each song's audio file, which can be extracted to form the basis for both the genre classification and the content-based song recommendations.

## Dataset
GTZAN Dataset (pre-labelled) @ https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

## Requirements
The model can be downloaded and executed remotely/locally in a conda environment running on Windows WSL, MacOS, or any major Linux distro. The required dependencies to be installed on the environment beforehand are:
1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. Librosa
6. Scikit-Learn
7. TensorFlow (GPU version)

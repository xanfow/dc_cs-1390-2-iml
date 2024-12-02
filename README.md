# Music Genre Classification + Recommendation Project by Divyam Chaudhary
This is Divyam Chaudhary's (1020221520) final project for Introduction to Machine Learning (CS-1390/PHY-1390-2) with Prof. Sandeep Juneja on the thesis: Music Genre Classification and Content-Based Recommendation System.

## Project Report
[add link]

## Overview
Traditional music recommendation systems rely heavily on collaborative filtering, which suggests music based on the listening behavior of other users with similar tastes. While this method can be effective, it often fails to consider the actual audio characteristics of songs, potentially limiting the diversity and accuracy of the recommendations. With this project, I aim to develop a machine learning model (a CNN in particular) to classify music based on genre and build a recommendation system that suggests songs to users based on similarities in the songs they listen to. I aim to improve recommendation accuracy by focusing on content-based similarities such as rhythm, mood, harmony, associated emotions, etc. These features are aptly captured in the MFCCs (mel-frequency cepstral coefficients) of each song's audio file, which can be extracted to form the basis for both the genre classification and the content-based song recommendations.

## Dataset
GTZAN Dataset (pre-labelled) @ https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

## Requirements
**I recommend uploading this repo to GDrive and then using Google Colab with T4 GPU runtime to most accurately replicate the results I achieved.**

With that said, the model can obviously be downloaded and executed remotely/locally, and will require the following dependencies to be installed on the system:

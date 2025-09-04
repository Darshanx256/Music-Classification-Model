# Music Genre Classifier 🎵

A lightweight and accurate music genre classification tool built using filtered tracks from the **GTZAN dataset**. This classifier predicts the genre of a music file by processing its Mel spectrograms through a Convolutional Neural Network (CNN).

---

## 📌 Overview

This classifier detects the genre of an audio file (MP3/WAV) using deep learning. It utilizes **Mel Spectrograms** and a **CNN architecture** trained on the GTZAN dataset which is a widely used benchmark containing tracks labeled under 10 genres.

Genres:  
`blues`, `classical`, `country`, `disco`, `hiphop`, `jazz`, `metal`, `pop`, `reggae`, `rock`

---

## 🎯 Objectives

- Ensure all training tracks are normalized and of equal length  
- Understand genre classification through similar works and design CNN accordingly  
- Use **Google Colab (GPU)** to efficiently train the model  
- Provide a clean notebook interface for:
  - Audio upload  
  - Genre prediction  
  - Waveform visualization  
- Keep the model lightweight and friendly for local systems

---

## ✅ Results

- Achieved **62% accuracy**, approaching human-level genre classification (~70%)  
- Displays the **top 3 predicted genres** along with **confidence scores** (up to 2 decimal places)  
- No signs of overfitting or underfitting  
- Trained using a filtered version of the GTZAN dataset (ensuring length & quality consistency)

---

## ⚠️ Limitations

- Certain genre overlaps (e.g., rock vs metal, blues vs jazz) affected accuracy — a common challenge even for humans  
- Slightly lower performance on **blues** and **rock** genres compared to others

---

## 📂 How to Use

1. Upload an audio file (.mp3 or .wav)
2. Model will slice the audio into segments, extract Mel spectrograms, and run predictions
3. View the top 3 predicted genres with confidence
4. Waveform of the audio is visualized
   Note: make sure that Music_Genre_Classifier notebook and gtzan_melspectro.keras model exists in the same directory

---

## 🛠️ Built With

- TensorFlow / Keras  
- Librosa  
- NumPy  
- Scikit-learn  
- Google Colab (GPU)

---

## 📁 Dataset

Filtered version of the **GTZAN Genre Collection**.  
Original GTZAN fetched from Kaggle : https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

---

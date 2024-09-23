# 🎶 Music Generation using LSTM

![MIT License](https://img.shields.io/badge/license-MIT-blue.svg) 
![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg) 
![Issues](https://img.shields.io/github/issues/Ashwintomar/LSTMusic.svg)

## 📚 Table of Contents
- [🔍 Introduction](#introduction)
- [📦 Dataset](#dataset)
- [🛠️ Usage](#usage)
- [🏗️ Model Architecture](#model-architecture)
- [🏋️‍♂️ Training](#training)
- [📈 Results](#results)
- [📜 License](#license)

## 🔍 Introduction
This project aims to generate classical music compositions using a Long Short-Term Memory (LSTM) neural network. It leverages the power of deep learning and a dataset consisting of MIDI files from various classical composers.

## 📦 Dataset
The dataset consists of MIDI files from 19 famous classical composers, scraped from [piano-midi.de](http://www.piano-midi.de). It contains a rich collection of classical compositions, providing a diverse training set for the model.

## 🛠️ Usage
1. Preprocess the MIDI dataset.
2. Train the LSTM-based model on the preprocessed data.
3. Generate new music compositions using the trained model.

## 🏗️ Model Architecture
The music generation model is based on a Bidirectional LSTM neural network, designed to capture sequential dependencies in the music data. The architecture includes dropout layers to prevent overfitting.

## 🏋️‍♂️ Training
The model was trained using the preprocessed MIDI dataset. Training parameters and progress can be found in the Training Notebook.

## 📈 Results
The model generates classical music compositions based on the training data. You can listen to the generated music in the repository's MIDI files.

## 📜 License
This project is licensed under the MIT License.

## 🔗 Repository
You can find the project on [GitHub](https://github.com/Ashwintomar/LSTMusic.git).

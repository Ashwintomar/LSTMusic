# Music Generation using LSTM

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [License](#license)

## Introduction

This project aims to generate classical music compositions using a Long Short-Term Memory (LSTM) neural network. It leverages the power of deep learning and a dataset consisting of MIDI files from various classical composers.

## Dataset

The dataset consists of MIDI files from 19 famous classical composers, scraped from [piano-midi.de](http://www.piano-midi.de). It contains a rich collection of classical compositions, providing a diverse training set for the model.

## Usage
- Preprocess the MIDI dataset.
- Train the LSTM-based model on the preprocessed data.
- Generate new music compositions using the trained model.

## Model Architecture
The music generation model is based on a Bidirectional LSTM neural network, designed to capture sequential dependencies in the music data. The architecture includes dropout layers to prevent overfitting.

## Training
The model was trained using the preprocessed MIDI dataset. Training parameters and progress can be found in the Training Notebook.

## Results
The model generates classical music compositions according to compositions provided. You can listen to the generated music in repository's midi file.

## License
This project is licensed under the MIT License.

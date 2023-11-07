<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://img.shields.io/badge/license-MIT-blue.svg">
</head>

<body>
    <h1>Music Generation using LSTM</h1>
    <hr>
    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#dataset">Dataset</a></li>
        <li><a href="#model-architecture">Model Architecture</a></li>
        <li><a href="#training">Training</a></li>
        <li><a href="#results">Results</a></li>
        <li><a href="#license">License</a></li>
    </ul>
    <h2 id="introduction">Introduction</h2>
    <p>This project aims to generate classical music compositions using a Long Short-Term Memory (LSTM) neural network. It leverages the power of deep learning and a dataset consisting of MIDI files from various classical composers.</p>
    <h2 id="dataset">Dataset</h2>
    <p>The dataset consists of MIDI files from 19 famous classical composers, scraped from <a href="http://www.piano-midi.de" target="_blank">piano-midi.de</a>. It contains a rich collection of classical compositions, providing a diverse training set for the model.</p>
    <h2>Usage</h2>
    <ul>
        <li>Preprocess the MIDI dataset.</li>
        <li>Train the LSTM-based model on the preprocessed data.</li>
        <li>Generate new music compositions using the trained model.</li>
    </ul>
    <h2 id="model-architecture">Model Architecture</h2>
    <p>The music generation model is based on a Bidirectional LSTM neural network, designed to capture sequential dependencies in the music data. The architecture includes dropout layers to prevent overfitting.</p>
    <h2 id="training">Training</h2>
    <p>The model was trained using the preprocessed MIDI dataset. Training parameters and progress can be found in the Training Notebook.</p>
    <h2 id="results">Results</h2>
    <p>The model generates classical music compositions according to the compositions provided. You can listen to the generated music in the repository's MIDI files.</p>
    <h2 id="license">License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>

</html>

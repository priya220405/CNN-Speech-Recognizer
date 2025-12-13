# 🗣️ CNN-Based Speech Recognition System

## 🎯 Project Goal
To develop a robust audio classifier capable of recognizing distinct spoken commands (e.g., "up," "down," "stop") and converting speech input into text using Python libraries.

## 🧠 Technical Architecture
The core of this system is a Convolutional Neural Network (CNN) optimized for audio classification.

### 1. Feature Extraction: MFCC
Instead of raw audio, the model is trained on **Mel-Frequency Cepstral Coefficients (MFCCs)**.  MFCCs are highly effective features that represent the short-term power spectrum of a sound.

### 2. Deep Learning Model: CNN
The **CNN** is used for classification due to its strength in pattern recognition, treating the MFCC output like an image to identify audio patterns associated with specific commands.

## 📊 Performance & Capabilities
* **Accuracy:** Achieved a classification accuracy of **[Insert Your Actual Accuracy Here, e.g., 92%]** on the test set.
* **Key Functionality:** Successfully recognizes **[Number]** distinct spoken commands and integrates with the `SpeechRecognition` library for general speech-to-text conversion.

## 🛠️ Technology Stack
* **Language:** Python 3
* **Core Libraries:** `TensorFlow/Keras` (for the CNN), `librosa` (for MFCC extraction and audio handling), `SpeechRecognition`.

## 💡 Running the System
1.  **Clone the repository:** `git clone https://github.com/priya220405/CNN-Speech-Recognizer.git`
2.  **Install dependencies:** `pip install librosa tensorflow SpeechRecognition`
3.  Execute the main script to start the recognition service.

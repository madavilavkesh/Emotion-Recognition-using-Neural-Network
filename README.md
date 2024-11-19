# Emotion Recognition Using Neural Network
A real-time emotion recognition system built using neural networks that classifies emotions from speech data based on extracted audio features.

### Project Overview
This project utilizes the RAVDESS dataset to classify emotions such as calm, happy, fearful, and disgust. It employs feature extraction techniques to analyze audio signals and trains a neural network for emotion recognition.

### Features
- **Audio Feature Extraction**: Extracted MFCC, chroma, and mel-spectrogram features using Librosa.
- **Model Architecture**: Built an MLP classifier using scikit-learn to identify emotions from audio data.
- **Performance Evaluation**: Evaluated the model using accuracy metrics and visualized training loss using Matplotlib.

## Tools and Libraries
- **Librosa**: For feature extraction from audio signals.
- **Soundfile**: For reading audio files in various formats.
- **scikit-learn**: For building and training the MLP classifier.
- **Matplotlib**: For visualizing model performance.

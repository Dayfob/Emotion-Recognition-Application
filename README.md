---

# Emotion Recognition Application

This repository contains the code and resources for an Emotion Recognition Application designed to assist individuals with Autism Spectrum Disorder (ASD) and anxiety disorders. The application utilizes advanced machine learning techniques to recognize and interpret emotional cues from audio data, providing real-time feedback to users.

## Project Overview

Emotion recognition is a significant challenge for individuals with ASD and anxiety disorders, often leading to social difficulties and increased stress. This project aims to create an assistive tool that enhances emotional awareness and facilitates better social interactions for these individuals.

### Key Features

- **Real-Time Emotion Detection:** The application processes audio input to detect emotions such as happiness, sadness, anger, fear, and more, providing immediate feedback to the user.
- **User-Centric Design:** Tailored for individuals with ASD and anxiety, the app focuses on ease of use and accessibility.
- **Advanced Machine Learning Models:** Utilizes state-of-the-art models like Convolutional Neural Networks (CNN) and Transformer Neural Networks (TNN) for high accuracy.

## Datasets

The application is trained on the following publicly available datasets:

- **[CREMA-D](https://www.kaggle.com/datasets/dmitrybabko/speech-emotion-recognition-en):** A dataset containing 7,442 audio files portraying various emotions.
- **RAVDESS:** Comprises 1,440 audio files with acted emotional speech.
- **SAVEE:** Includes 480 files of male actors' emotional speech.
- **TESS:** Contains 2,800 files portraying emotions by older and younger female actors.

## Audio Features

The following audio features are extracted and used for training the models:

- **Zero Crossing Rate (ZCR)**
- **Chromagram**
- **Spectral Contrast**
- **Spectral Rolloff**
- **Root Mean Square (RMS)**
- **Mel Spectrogram**
- **Mel-Frequency Cepstral Coefficients (MFCC)**

## Machine Learning Models

Several machine learning algorithms were explored, with the following showing the best performance:

- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Convolutional Neural Networks (CNN)**
- **Transformer Neural Networks (TNN)**

The CNN and TNN models exhibited the highest accuracy in recognizing emotions, with specific fine-tuning to minimize overfitting and enhance generalization.

## Tools and Libraries

- **Programming Language:** Python
- **Development Environment:** PyCharm, Jupyter Notebooks
- **Libraries:** PyTorch, scikit-learn, Pandas, Numpy, Librosa, PyAudio, SoundFile

## Future Work

Planned future improvements include:

- Enhancing model accuracy through data augmentation and the introduction of more complex neural networks.
- Expanding the dataset to include additional languages and cultural contexts.
- Incorporating real-time emotion detection capabilities for a more interactive user experience.

## Conclusion

This project represents a significant step forward in developing assistive technologies for individuals with ASD and anxiety disorders. By leveraging advanced machine learning techniques, this application provides a valuable tool for improving emotional understanding and social interactions.

## Contributors

- **Alikhan Semembayev** - [University of the Pacific](mailto:asemembayev@u.pacific.edu)
- **Anmol Singh** - [University of the Pacific](mailto:a_singh51@u.pacific.edu)
- **Abbas Hussain Syed** - [University of the Pacific](mailto:a_syed3@u.pacific.edu)

---

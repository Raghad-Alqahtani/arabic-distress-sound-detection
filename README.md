# Arabic Distress Sound Detection Using Deep Learning

A CNN-based audio classification system designed to detect Arabic distress sounds from audio recordings using Log-Mel Spectrogram features.

## Project Overview

This project focuses on detecting Arabic distress sounds and distinguishing them from non-distress sounds using deep learning techniques.

The system processes audio recordings, extracts Log-Mel Spectrogram features, and uses a Convolutional Neural Network (CNN) for classification.

## Features

- Arabic distress sound classification
- Audio preprocessing and normalization
- Log-Mel Spectrogram feature extraction
- CNN-based audio classification
- Data augmentation using noise and pitch variation
- Logistic Regression baseline comparison
- Model evaluation using Accuracy, F1-score, and ROC-AUC

## Technologies

- Python
- TensorFlow / Keras
- Librosa
- Scikit-learn
- NumPy
- Matplotlib

## Dataset

The project uses 50 Arabic audio clips divided into two classes:

- `disaster`
- `non_disaster`

The dataset was split into training, validation, and testing sets using a 70/15/15 split.

## Model

The proposed CNN consists of three convolutional blocks followed by Global Average Pooling, Dropout, and a binary classification layer.

Audio recordings are converted into Log-Mel Spectrogram representations before being passed to the CNN.

## Results

The CNN achieved the following results on the test set:

| Metric | Score |
|---|---:|
| Test Accuracy | 87.5% |
| F1-Score | 0.909 |
| ROC-AUC | 0.667 |

## Project Structure

```text
arabic-distress-sound-detection/
│
├── README.md
└── Arabic_Distress_CNN_Code.pdf
```
## Future Work

Future improvements include expanding the dataset, improving the model architecture and data augmentation techniques, and exploring real-time deployment for portable devices.

Author

Raghad Nasser

# Assignment 09 – Audio Classification using Deep Learning, STT and TTS

## Objective
To design and implement a deep learning application for audio classification using a Convolutional Neural Network (CNN), integrated with Speech-to-Text (STT) and Text-to-Speech (TTS) functionalities.

## Dataset
Google Speech Commands Dataset
The dataset contains short audio recordings of spoken words and commands. A subset of the dataset is used for training, validation, and testing.

## Model Used
Convolutional Neural Network (CNN)
The CNN classifies audio recordings using spectrograms generated from audio waveforms.

## Tasks Performed
- Loaded the Speech Commands dataset
- Preprocessed audio waveforms
- Converted audio signals into spectrograms
- Built a CNN-based audio classification model
- Trained the model for audio classification
- Evaluated the model using test accuracy
- Generated a classification report
- Visualized the confusion matrix
- Plotted training and validation accuracy
- Integrated Speech-to-Text using SpeechRecognition
- Classified uploaded audio recordings using the trained CNN
- Integrated Text-to-Speech using gTTS
- Generated spoken classification results
- Saved the trained CNN model

## System Workflow

Load Audio Dataset
        ↓
Preprocess Audio
        ↓
Generate Spectrograms
        ↓
Build and Train CNN
        ↓
Evaluate Model
        ↓
Upload Audio Recording
        ↓
Speech-to-Text (STT)
        ↓
CNN Audio Classification
        ↓
Text-to-Speech (TTS)
        ↓
Save Trained Model

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Tools and Technologies
- Python
- Google Colab
- TensorFlow / Keras
- TensorFlow Datasets
- TensorFlow I/O
- NumPy
- Matplotlib
- Scikit-learn
- SpeechRecognition
- Google Text-to-Speech (gTTS)

## Result
A CNN-based audio classification system was developed using the Speech Commands dataset. The system evaluates classification performance using accuracy and other classification metrics. It also integrates STT to transcribe spoken commands and TTS to speak the classification result.

## Requirements

Speech recognition through Google's service and gTTS require an internet connection. Audio recordings should be provided in a supported WAV format for the notebook's audio-processing workflow.

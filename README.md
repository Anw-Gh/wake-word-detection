# Wake Word Detection

This project focuses on detecting wake words using TensorFlow. It involves collecting and processing audio data, feature extraction, model training, and evaluation.

## Data Collection
- **Fluent-Speech-Corpus**: Used for negative samples (does not contain the wake word).
- **Alexa Dataset**: Utilized for positive samples (contains the wake word).
- **Background Noise**: Collected from various sources and saved on the drive.
- **Telegram Bot**: Developed to collect additional dataset from people.

## Data Preprocessing
- **DeepFilterNet**: Applied to remove silent segments from Alexa’s audio clips.
- **Data Augmentation**: Employed to duplicate and enhance the dataset.

## Feature Extraction
- **Spectrogram**: Used to convert audio signals into visual representations for model input.

## Model Structure
- **GRU Units**: Implemented in the model to process the sequential audio data.

## Training and Testing
- The model was trained and tested; however, the results were not satisfactory.

## To-Do
- Explore alternative methods for training:
  - **LSTM Units**: Consider using LSTM units to potentially improve model performance.
  - fixing some bugs.



*** The code was modified from a part of (Trigger Word Detection - Sequence Models - DeepLearning.AI - coursera)


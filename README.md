<center><h1>Music Genre Classification using Deep Learning</h1></center>

## Project Description

This project aims to classify music genres using deep learning techniques. The GTZAN dataset from Kaggle is used for training and evaluation. The dataset consists of audio files from various music genres, including blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock.

The main objective of this project is to develop a deep learning model that can accurately classify music genres based on their audio features. The model will be trained on a subset of the GTZAN dataset, and its performance will be evaluated on a separate test set.

## Dataset

The GTZAN dataset contains 10 music genres, with each genre having approximately 100 audio samples. Each audio sample is 30 seconds long and has a sample rate of 22,050 Hz. The audio files are in WAV format.

## Methodology

The project will follow the following steps:

1. Data Preprocessing: The audio files will be preprocessed to extract relevant features, such as Mel-frequency cepstral coefficients (MFCCs), spectral contrast, and tonal centroid. These features will be used as inputs to the deep learning model.

2. Model Development: A deep learning model will be developed using convolutional neural networks (CNNs) or recurrent neural networks (RNNs) to classify music genres. The model architecture will be designed to effectively capture the temporal and spectral characteristics of the audio signals.

3. Model Training: The model will be trained on a subset of the GTZAN dataset using an appropriate loss function and optimization algorithm. The training process will involve iterating over the training data multiple times (epochs) to minimize the loss and improve the model's performance.

4. Model Evaluation: The trained model will be evaluated on a separate test set to assess its performance in classifying music genres. The evaluation metrics, such as accuracy, precision, recall, and F1 score, will be used to measure the model's effectiveness.

5. Model Deployment: Once the model is trained and evaluated, it can be deployed to classify music genres in real-world scenarios. The model can be integrated into music streaming platforms or used as a standalone application.

## Conclusion

By successfully developing a deep learning model for music genre classification, this project aims to contribute to the field of music analysis and provide a valuable tool for music recommendation systems, music information retrieval, and other related applications.

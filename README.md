Audio Classification: Cat and Dog
This repository contains code for an audio classification project focused on distinguishing between cat and dog audio samples. The project utilizes deep learning techniques to train a model capable of accurately classifying audio recordings as either cat or dog.

DATASET:
The dataset used for this project consists of a collection of audio samples labeled as either cat or dog. The audio files are in WAV format and are split into training and testing sets. The dataset can be obtained from
https://www.kaggle.com/datasets/mmoreaux/audio-cats-and-dogs .

Feature Extraction:
The audio samples undergo feature extraction to convert the raw audio data into a format suitable for machine learning models. The following feature extraction techniques are applied:

Mel Frequency Cepstral Coefficients (MFCC):
MFCCs are widely used features in audio processing. They capture the spectral characteristics of the audio signals, providing information about the shape of the vocal tract.

Spectrogram: 
Spectrograms are visual representations of the frequencies present in an audio signal over time. They are obtained by applying a Fourier transform to short, overlapping segments of the audio signal.

Model Architecture:
The classification model is built using deep learning techniques, specifically using a convolutional neural network (CNN) architecture. The CNN is designed to extract relevant features from the audio data and classify them into the respective categories. The model is implemented using libraries like - Librosa, IPython.Display,Tesnorflow,Sklearn.

Results
The model achieved an accuracy of 90% on the test set. More details about the training process and results can be found in py file.

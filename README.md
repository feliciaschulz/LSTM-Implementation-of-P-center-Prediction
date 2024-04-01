# LSTM-Implementation-of-P-center-Prediction

### Introduction
This is the repository associated with the paper **Predicting Perceptual Centers Located at Vowel Onset in German Speech Using Long Short-Term Memory Networks** by Schulz, F., De Sisto, M.,  Roncaglia-Denissen, M. P. and Hendrix, P. (2023)
Access the paper here: https://www.isca-archive.org/interspeech_2023/schulz23_interspeech.html

Perceptual centers (p-centers) can be defined as the perceived centers of a syllable. Previous research regarding the location of p-centers in speech relied on experimental methods, and among the suggested acoustic features contributing to the location of p-centers in Germanic languages is the transition of the consonant to the vowel onset. The current study investigates the prediction of the location of p-centers in German, by means of machine learning. Machine learning is a promising tool to capture possible non-linear relationships that may occur among the acoustic features used in the complexity that is the human perception. Therefore, an LSTM neural network approach was used for the identification of p-centers in a set of spoken German sentences, with input data features being Mel Frequency Cepstral Coefficients (MFCC), amplitude envelope and root mean squared energy. The model was able to achieve a balanced accuracy of 84% with MFCCs being the best predictor of p-center location.

### Repository structure
The full pipeline for the data preprocessing, feature extraction and LSTM implementation can be found in the Jupyter Notebook "PredictingPerceptualCenters.ipynb". An example for the input audio data can be found in the DATA_SIGNALS comprising the file "example.wav". An example for the labelled input data is the textfile "P-centers.txt".

### Citation
Please cite as following:
Schulz, F., De Sisto, M., Roncaglia-Denissen, M.P., Hendrix, P. (2023) Predicting Perceptual Centers Located at Vowel Onset in German Speech Using Long Short-Term Memory Networks. Proc. INTERSPEECH 2023, 1793-1797, doi: 10.21437/Interspeech.2023-2154


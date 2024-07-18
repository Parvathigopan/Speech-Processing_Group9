# Animal Sound Recognition Using Deep Learning
This project focuses on the recognition of animal sounds using machine learning techniques, particularly neural networks. The goal is to classify sounds from various animals, such as cats, dogs, ducks, and horses, based on their audio recordings.

1. Introduction

Animal sound recognition is an emerging field that bridges bioacoustics and artificial intelligence. This project aims to interpret and categorize animal sounds for applications such as wildlife monitoring, conservation efforts, and understanding animal behavior.

2. Dataset

The dataset comprises recordings of various animal sounds. Each audio file was preprocessed to a uniform duration of two seconds, normalized, and prepared for feature extraction.

3. Methodology

Data Collection: Audio recordings of different animals were collected from publicly available datasets.

Preprocessing: Normalization of audio signals and trimming to consistent duration.

Feature Extraction: Root Mean Square (RMS) energy features were extracted using the Librosa library. Spectrograms were used to visualize the power distribution across frequencies.

Model Training: A Multi-Layer Perceptron (MLP) classifier was trained on the extracted features.

Evaluation: The model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score.

4. Results

The MLP classifier demonstrated high accuracy in distinguishing between different animal sounds. The model showed robustness and reliability, with high precision and recall for most animal classes. Spectrogram visualizations confirmed the classifier's effectiveness.

5. Conclusion

This project successfully applied machine learning techniques to classify animal sounds, highlighting the potential of machine learning in bioacoustics. The findings can aid in wildlife monitoring, conservation, and animal behavior research.

6. References

-Che Yong Yeo, S.A.R. Al-Haddad, and Chee Kyun Ng, "Animal Voice Recognition for Identification (ID) Detection System"

-Additional references are listed in the project report.

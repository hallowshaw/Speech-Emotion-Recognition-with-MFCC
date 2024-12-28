# Speech Emotion Recognition using MFCC(Mel-Frequency Cepstral Coefficients)

## Overview
Speech Emotion Recognition (SER) is a project that uses machine learning techniques to identify human emotions from speech signals. This repository demonstrates how to preprocess audio data, extract features, train models, and evaluate their performance for emotion classification.

## Features
- **Audio Feature Extraction**: Utilizes MFCCs (Mel-frequency cepstral coefficients) to extract relevant features from audio signals.
- **Emotion Classification**: Predicts emotions such as happiness, sadness, anger, and neutrality.
- **Model Training and Evaluation**: Implements machine learning models to classify emotions.
- **Visualization**: Includes visualizations for audio signal characteristics and performance metrics.

## Datasets
The project uses the following datasets:

1. **[RAVDESS]**: Ryerson Audio-Visual Database of Emotional Speech and Song. Contains audio recordings of speech performed with different emotions. [Link to dataset](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)
2. **[CREMA-D]**: Crowd-sourced Emotional Multimodal Actors Dataset. Includes audio-visual recordings with emotional expressions. [Link to dataset](https://www.kaggle.com/datasets/ejlok1/cremad)
3. **[TESS]**: Toronto Emotional Speech Set. Features emotional speech data recorded by female speakers. [Link to dataset](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)
4. **[SAVEE]**: Surrey Audio-Visual Expressed Emotion. Comprises audio recordings of speech expressing different emotions by male speakers. [Link to dataset](https://www.kaggle.com/datasets/ejlok1/surrey-audiovisual-expressed-emotion-savee)

Please download these datasets from the provided links and place them in the appropriate folder structure.

## Prerequisites

- Python 3.7+
- Required Libraries:
  - `numpy`: For numerical operations and handling arrays.
  - `librosa`: For audio processing and feature extraction.
  - `matplotlib`: For creating visualizations.
  - `scikit-learn`: For implementing machine learning models and evaluation metrics.
  - `seaborn`: For enhanced data visualization.

Install the required libraries using the following commands:

```bash
pip install numpy librosa matplotlib scikit-learn seaborn
```

## Contribution
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Acknowledgments
Inspiration for the project from various open-source emotion recognition research.  
I took help from [this Kaggle notebook on Speech Emotion Recognition](https://www.kaggle.com/code/shivamburnwal/speech-emotion-recognition).






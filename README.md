# Music Genre Classification

Welcome to the **Music Genre Classification** repository! This project aims to classify music tracks into different genres using feature extraction and machine learning techniques. 

## 📦 Project Overview

This project leverages audio feature extraction and machine learning to classify music tracks into genres such as Progressive Rock, Non-Progressive Rock, and Djent. The repository includes code for feature extraction, dataset preparation, model training, and error logging.

## 🔧 Features

- **Feature Extraction:** Extracts key audio features such as chroma STFT, RMSE, spectral centroid, spectral bandwidth, rolloff, zero-crossing rate, and MFCCs.
- **Data Handling:** Scripts to process and clean datasets, handle audio files of various formats, and manage feature extraction errors.
- **Classification:** Machine learning models to classify audio tracks based on extracted features.
- **Error Logging:** Maintains logs for error handling during feature extraction.

## 📁 Directory Structure

```plaintext
Music-Genre-Classification/
│
├── Training_set/
│   ├── Progressive_Rock_Songs/
│   └── Not_Progressive_Rock/
│
├── Test_set/
│   ├── Other/
│
├── features/
│   ├── training_features.csv
│   └── test_features.csv
│
├── scripts/
│   ├── extract_features.py
│   ├── classify_music.py
│   └── additional_scripts.py
│
├── error_logs.txt
├── README.md
└── requirements.txt
```

## 🚀 Getting Started

To get started with this project, clone the repository and install the required dependencies.

### Clone the Repository

```bash
git clone https://github.com/yourusername/music-genre-classification.git
cd music-genre-classification
```

### Install Dependencies

Ensure you have Python 3.7+ installed. Then, install the required packages using pip:

```bash
pip install -r requirements.txt
```

### Feature Extraction

To extract features from audio files, run the `extract_features.py` script. This script processes both training and test datasets.

```bash
python scripts/extract_features.py
```

### Music Classification

Once feature extraction is complete, you can classify the music tracks using the `classify_music.py` script. This script trains the machine learning model and evaluates its performance.

```bash
python scripts/classify_music.py
```

### Error Handling

Check `error_logs.txt` for any errors that occurred during feature extraction or classification.

## 🛠️ Dependencies

This project uses the following libraries:

- `librosa`
- `numpy`
- `scipy`
- `matplotlib`
- `pandas`
- `scikit-learn` (for model training and evaluation)

Install the dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## 📜 Acknowledgments

- [Librosa](https://librosa.org/) - Python package for music and audio analysis.
- [NumPy](https://numpy.org/) - Library for numerical computations.
- [Matplotlib](https://matplotlib.org/) - Plotting library for Python.

---

This README includes instructions for both the feature extraction and classification processes. Adjust the content to fit the specifics of your scripts and project setup.
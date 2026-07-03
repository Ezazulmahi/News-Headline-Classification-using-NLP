# News Headline Classification using NLP

## Overview

This project implements a News Headline Classification system using Natural Language Processing (NLP) and Machine Learning. The objective is to classify news headlines into predefined categories based on their textual content.

The project includes data preprocessing, feature extraction using TF-IDF, model training, evaluation, and prediction of news topics.

---

## Dataset

The dataset contains the following columns:

| Column        | Description                      |
| ------------- | -------------------------------- |
| News Headline | The text of the news headline    |
| News Topic    | The corresponding category label |

Example:

| News Headline                | News Topic             |
| ---------------------------- | ---------------------- |
| IBM Starts New AI Initiative | Science and Technology |
| Seattle Wins Championship    | Sports                 |
| Oil Prices Continue Rising   | Business               |
| International Leaders Meet   | World News             |

---

## Objective

The goal of this project is to build a machine learning model capable of accurately classifying unseen news headlines into their corresponding news topics.

---

## Features

* HTML tag removal
* Text preprocessing and cleaning
* TF-IDF feature extraction
* Machine learning-based text classification
* Model evaluation
* Prediction on new news headlines

---

## Technologies Used

* Python
* Pandas
* NumPy
* BeautifulSoup4
* NLTK
* Scikit-learn
* Joblib

---

## Project Structure

```
News-Headline-Classification-using-NLP/
│
├── dataset/
│   └── news_dataset.csv
│
├── news_classifier.py
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Ezazulmahi/News-Headline-Classification-using-NLP.git
```

Navigate to the project directory:

```bash
cd News-Headline-Classification-using-NLP
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Run the Python script using:

```bash
python news_classifier.py
```

---

## Workflow

1. Load the dataset.
2. Remove HTML tags from the headlines.
3. Clean and preprocess the text.
4. Split the dataset into training and testing sets.
5. Convert text into numerical features using TF-IDF.
6. Train the classification model.
7. Evaluate the model using standard classification metrics.
8. Predict the category of new news headlines.

---

## Evaluation Metrics

The model is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## Example Prediction

Input:

```
Apple launches its latest AI-powered MacBook.
```

Predicted Output:

```
Science and Technology
```

---

## Future Work

* Implement deep learning models such as LSTM and GRU.
* Experiment with transformer-based models such as BERT.
* Perform hyperparameter tuning.
* Develop a web interface for interactive predictions.
* Deploy the model as a web service.

---

## Author

Md. Ezazul Haque Mahi

B.Sc. in Computer Science and Engineering

BRAC University



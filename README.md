# Fake News Detection

A machine learning project for classifying news headlines as **real or fake** using Natural Language Processing (NLP) and supervised machine learning techniques.

## Project Overview

This project processes news headline text and uses machine learning to classify it as real or fake. The workflow includes text preprocessing, feature extraction, model training, and evaluation.

## Technologies Used

* Python
* Pandas
* NLTK
* Scikit-learn
* Regular Expressions (Regex)

## Dataset

The project uses the **FakeNewsNet** dataset for fake-news classification.

## Methodology

The project follows these main steps:

1. Load and inspect the dataset.
2. Clean and preprocess the news headline text.
3. Remove stopwords using NLTK.
4. Apply Porter stemming.
5. Convert text into numerical features using the **Bag-of-Words** approach.
6. Split the data into training and testing sets using an **80/20 split**.
7. Train a **Multinomial Naive Bayes** classification model.
8. Evaluate the model using accuracy and a confusion matrix.

## Model

**Multinomial Naive Bayes**

The model is trained on the processed headline features and used to classify news as real or fake.

## Results

The model achieved **83.1% accuracy** on the evaluation data.

A confusion matrix was also used to analyze the classification results.

## Project File

* [`Fake_News_Detection.ipynb`](./Fake_News_Detection.ipynb) — Complete Google Colab/Jupyter Notebook containing the data preprocessing, model training, and evaluation workflow.

## How to Run

1. Open `Fake_News_Detection.ipynb`.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries if necessary.
4. Run the notebook cells in order.

## Author

**Datta Adari**

GitHub: [adaridatta9090](https://github.com/adaridatta9090)

# BIL-NEWS-PROJ

# News Classification System

This project implements a news classification system using machine learning to differentiate between 'REAL' and 'FAKE' news articles. It leverages various Python libraries including `numpy`, `pandas`, `scikit-learn`, and `seaborn` for data processing, model training, and visualization.

## Project Overview

The system performs the following tasks:
1. **Data Loading**: Reads news data from a CSV file.
2. **Data Exploration**: Displays the initial rows and structure of the dataset.
3. **Feature Extraction**: Converts text data into numerical features using TF-IDF vectorization.
4. **Model Training**: Trains a Passive Aggressive Classifier to classify news as 'REAL' or 'FAKE'.
5. **Evaluation**: Evaluates the model performance and generates confusion matrices.

## Requirements

- Python 3.x
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the necessary packages using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn


## Project Structure
   news.csv: CSV file containing the news data with columns title, text, and label.
   news_classification.ipynb: Jupyter notebook containing the code for loading, processing, and classifying the news data.

## Usage
1. Load the Dataset: The dataset is loaded from a CSV file located at D:\\College\\Bhushan\\sem6\\New folder\\DMBI\\news.csv. Ensure this file path is correctly specified in the notebook.

2. Explore the Data:  The initial rows and the structure of the dataset are displayed to understand its contents.

3. Train the Model: The PassiveAggressiveClassifier is used for training the model to classify news articles.

4. Evaluate the Model: The model's performance is evaluated using accuracy and confusion matrices, visualized with seaborn.

## Made by Nishant Acharekar

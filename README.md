# 🎬 Movie_Genre_Classification

This project aims to classify movies into different genres based on provided metadata such as movie titles, overviews, tags, and more. It applies Natural Language Processing (NLP) techniques and machine learning models to predict the appropriate genres for a given movie description.

## 📂 Dataset

The dataset for this project must be **imported from Kaggle**.

You can find and download the dataset [here](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb) by searching for **Movie Genre Classification** datasets.  
After downloading, place the data files in the appropriate project directory (`/data/` or the specified path in the code).

> **Note:** Make sure you have a Kaggle account to access and download the dataset.

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Movie_Genre_Classification.git
   cd Movie_Genre_Classification
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Set up a virtual environment for clean dependency management:
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/Mac
   .\env\Scripts\activate   # For Windows
   ```

## 🚀 Features

- Text preprocessing (cleaning, tokenization, stemming/lemmatization)
- Feature extraction using TF-IDF, word embeddings, etc.
- Multi-label genre classification
- Model evaluation and performance metrics
- Visualization of results

## 📈 Models Used

- Logistic Regression
- Random Forest
- Naive Bayes
- K Neighbours Classifier
- Support Vector Machines

## 🧠 Future Improvements

- Experiment with more advanced models like BERT, RoBERTa
- Hyperparameter tuning for better accuracy
- Deploy the model using a web application (Flask/Streamlit)

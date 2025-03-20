# Rotten Tomatoes Sentiment Analysis and Exploratory Data Analysis (EDA)

## Overview
This Jupyter Notebook performs **Exploratory Data Analysis (EDA) and Sentiment Classification** on the **Rotten Tomatoes movie reviews dataset**. The dataset contains movie reviews along with sentiment labels, making it an ideal candidate for text analysis and machine learning-based sentiment classification.

## Dataset
The dataset is sourced from Rotten Tomatoes and can be found [here](https://www.kaggle.com/datasets/andrezaza/clapper-massive-rotten-tomatoes-movies-and-reviews).

## Requirements
To run this notebook, you need to install the following dependencies:
```bash
pip install gdown sweetviz fast-langdetect langdetect contractions
```

## Steps Performed in This Notebook

### 1. Importing Libraries
Necessary Python libraries for data manipulation, visualization, and natural language processing (NLP) are imported.

### 2. Data Acquisition
The dataset is downloaded using `gdown` from a public Google Drive link and loaded into a Pandas DataFrame.

### 3. Data Preprocessing
- Handling missing values
- Language detection and filtering
- Converting contractions into standard words for NLP processing
- Tokenization and text cleaning

### 4. Exploratory Data Analysis (EDA)
EDA is performed to gain insights into the dataset, using:
- Summary statistics
- Word clouds
- Sentiment distribution plots
- Frequent words and n-grams

### 5. Sentiment Classification
A machine learning model is trained to classify sentiment as positive or negative based on the review text. Methods used include:
- Text vectorization (TF-IDF, CountVectorizer, etc.)
- Supervised learning classifiers such as Logistic Regression, Naive Bayes, or Neural Networks

## Results
The notebook evaluates the performance of sentiment classification models using accuracy, precision, recall, and F1-score. Key insights into how sentiment is distributed across the dataset are also highlighted.

## How to Use
1. Clone the repository and download the dataset.
2. Install the required dependencies.
3. Run the notebook step by step to analyze the data and build the sentiment classification model.

## Author
This notebook was created for educational and analytical purposes.

## License
This project is licensed under the MIT License.
